# OnlineSurvey Help Center, writing instructions

This is the help center at help.onlinesurvey.ai, built on [Mintlify](https://mintlify.com). Pages are MDX with YAML frontmatter; `docs.json` holds the site config and navigation; `style.css` is injected on every page. The site deploys from `main`, so every change is a pull request.

The product source of truth is the OnlineSurvey monorepo, not this repo. Never state a fact about the product that you did not read in the monorepo or see in the running app:

- UI labels: `apps/web-app/src/messages/en.json` (keys `builder.*`, `survey.*`, `distribute.*`, `chrome.nav.*`)
- What is built and what is not: `docs/02-features.md`, sections "Built but not wired" and "Things that look like features and are not"
- Logic semantics: `docs/04-logic.md`, `packages/engine/src/commit.ts`
- Question kinds: `scripts/help/out/kind-facts.json` (generated from `packages/schema/src/capabilities/`; regenerate with `npx tsx scripts/help/kind-facts.mts`, never hand-edit)
- Plans and limits: `packages/billing/core/src/pricing/seed.ts`
- The respondent surface: `docs/06-fill.md`

## Voice

- Second person, present tense, active voice. "You" build the survey; "respondents" fill it in; "we" is OnlineSurvey.
- American spelling, matching the app: organization, color, customize.
- One idea per sentence. Short paragraphs. No marketing.
- No em dashes anywhere. Use a comma, a period, or a colon.
- No "simply", "just", "easily", "please".
- Never "disqualify". The word is "screen out" and the outcome is "Screened out".
- The four outcomes are always spelled: Completed, Screened out, Quota full, Quality reject.
- Name UI controls exactly as the app does, in bold: click **Publish**. Dialog titles in bold: **Skip from here**.
- A limit is a fact, stated plainly in a sentence. Never a `<Warning>`, never a `<Danger>`. `<Note>` and `<Tip>` at most once per page.
- Say what the product does today. Nothing "coming soon", nothing "planned". If a control does not exist in the app, the page does not mention it.

## Terminology

- survey, block, screen, page break, question, option, ending, outcome
- rule (a condition with an effect), branching, screen-out, show and hide, carry-forward, piping, randomization, variable, scoring, quota, loop
- organization, workspace, member, admin, owner, seat
- response, session, published version
- Not: "form", "field" (except inside a multi-field question), "logic jump", "disqualify", "page" (a page is a screen), "user" (an author or a respondent).

## Page skeletons

Every page of a type has the same headings in the same order, so the right-hand table of contents reads the same across siblings.

- Guide page: lead sentence, one screenshot placeholder, `## What it does`, `## Set it up`, `## Good to know`, `## Related`.
- Concept page (How a survey is built): `## What it is`, `## Why it matters`, `## See it in the builder`, `## Related`.
- Rules page: `## What it does`, `## Set it up`, `## Which questions have it`, `## Related`.
- Logic page: `## What it does`, `## Example`, `## Set it up`, `## Works with`, `## Good to know`, `## Related`.
- Question page: lead, a screenshot placeholder for the question as a respondent sees it, `## When to use it` (three bullets, then a **Consider instead:** line), `## Add it`, `## Settings`, `## Rules you can set`, `## Logic that works with it`, `## How it shows in results`, `## Related`.
- Family overview: lead, a `<CardGroup cols={3}>` of the kinds, `## Compare` table.

## Components

- `<Steps>` must contain `<Step title="...">` children. Bare `###` headings inside `<Steps>` render nothing.
- No `<Frame>` or `<img>` in a page yet. Where a screenshot belongs, write `{/* screenshot: <caption> */}` on its own line; the caption is what the picture will carry when it is captured.
- `<CardGroup cols={2|3}>` with `<Card title href>` for Related.
- `<Tabs>` only for the plan comparison. `<AccordionGroup>` only on Common issues.
- Links to other pages are root-relative: `[Quotas](/logic/quotas)`.

## Screenshots

There are no screenshots in the pages yet. Every place one belongs is an MDX comment on its own line, `{/* screenshot: ... */}`, and the text after the colon is the caption for that shot.

When they are captured they will come from a workspace and organization named for OnlineSurvey, never the dev workspace, so no placeholder name reaches a reader. The capture is driven by `scripts/dev/help-shots.mts` in the monorepo. Use the caption already written in the comment; do not reword it.

## Content boundaries

- Do not document: passwords on share links (not offered in the app), the speed trap (no control exists), saved contact-list management beyond what the add-recipients dialog offers, bounce or spam statuses from the mail provider, straight-lining detection, translation, MaxDiff, conjoint, Kano, Van Westendorp, a template gallery, save-and-resume across devices.
- Do not describe internal architecture, file paths, or code. A reader is an author or an admin, never a developer.
- Do not quote prices or limits from memory; read the pricing seed and say which plan.
