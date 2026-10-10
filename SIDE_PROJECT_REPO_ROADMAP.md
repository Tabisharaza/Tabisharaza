# Public Side Project Repo Roadmap

This roadmap converts the creative side-project backlog into public GitHub repositories and small, shippable products. Each project should remain narrow, portfolio-friendly, and easy to finish in free time.

## Execution Rule

- Every project should be a public GitHub repository.
- Every repo should include a clear README, MVP scope, tech stack, setup steps, screenshots/GIF placeholder, and next milestones.
- Keep each MVP small enough to build in 2-6 focused sessions.
- Avoid private company data, credentials, internal screenshots, and confidential workflow details.
- Prefer clean, practical demos over over-engineered platforms.

## Priority Repositories

### 1. cronweave
**Idea:** Visual cron schedule composer.

**MVP:**
- Human-friendly schedule controls.
- Live cron expression output.
- Plain-English explanation.
- Copy button.
- Example presets: daily backup, Monday report, every 15 minutes, monthly billing run.

**Repo status:** public repo already exists: `Tabisharaza/cronweave`.

### 2. retrycanvas
**Idea:** Beautiful retry/backoff visualizer for developers.

**MVP:**
- Input retry count, base delay, multiplier, max delay, jitter.
- Timeline visualization.
- Copyable config examples.
- Simple explanation of exponential backoff.

**Repo status:** public repo already exists: `Tabisharaza/retrycanvas`.

### 3. checkoutscout
**Idea:** Checkout/payment test-case helper.

**MVP:**
- Generate QA scenarios for coupon, VAT, refund, failed payment, wallet, and card flows.
- Export checklist as Markdown.
- Add common edge cases.

**Repo status:** public repo already exists: `Tabisharaza/checkoutscout`.

### 4. detourlab
**Idea:** Decision and scenario lab for product/process alternatives.

**MVP:**
- Add a decision.
- Add possible routes/options.
- Score by cost, effort, risk, confidence, and reversibility.
- Export a decision note.

**Repo status:** public repo already exists: `Tabisharaza/detourlab`.

### 5. fixturefolio
**Idea:** Household/facility inventory and maintenance tracker.

**MVP:**
- Add asset/item.
- Track purchase date, warranty, service date, next due date, cost, notes.
- Dashboard for upcoming renewals.

**Repo status:** public repo already exists: `Tabisharaza/fixturefolio`.

## New Public Repos To Create

### 6. permission-matrix-studio
**Idea:** Visual role-permission matrix builder.

**MVP:**
- Roles x actions grid.
- Export JSON/CSV.
- Generate positive/negative authorization test cases.
- Sample roles: Admin, Manager, Finance, Viewer, Guest.

### 7. rtl-ui-stress-tester
**Idea:** Arabic/English UI stress-testing playground.

**MVP:**
- Toggle LTR/RTL.
- Test cards, buttons, tables, forms, navbars.
- Long Arabic and English text cases.
- Highlight overflow and alignment issues.

### 8. webhook-aquarium
**Idea:** Local webhook event inspector.

**MVP:**
- Receive webhook payloads locally.
- Show event cards.
- Inspect headers/body/timestamp.
- Replay event.

### 9. screenshot-redactor
**Idea:** Simple screenshot privacy tool.

**MVP:**
- Upload/drag image.
- Draw redaction rectangles.
- Blur or solid mask.
- Export redacted image.

### 10. career-evidence-vault
**Idea:** Portfolio evidence tracker for interviews and performance reviews.

**MVP:**
- Store achievement, screenshot/link placeholder, impact, tech stack, date.
- Filter by role: developer, technical lead, IT manager, solution architect.
- Generate evidence pack Markdown.

### 11. tiny-office-tools
**Idea:** Collection of small Saudi office utilities.

**MVP tools:**
- VAT calculator.
- SAR/USD reimbursement calculator.
- Hijri/Gregorian note formatter.
- Arabic/English email format helper.

### 12. bug-museum
**Idea:** A museum-style archive of software bugs and lessons learned.

**MVP:**
- Bug title, symptoms, habitat, root cause, fix, lesson.
- Search and tags.
- Museum-card UI.

### 13. api-postcards
**Idea:** Tiny poetic APIs with useful or beautiful outputs.

**MVP endpoints:**
- `/quiet`
- `/sunset`
- `/focus`
- `/year/:year`
- `/proverb`

### 14. corporate-ghost-stories
**Idea:** Writing project for short office ghost stories.

**MVP:**
- Static website.
- 5 short stories.
- Dark reading mode.
- Tag by theme: printer, server, access card, old email, meeting room.

### 15. last-version
**Idea:** Short stories told as final software release notes.

**MVP:**
- Static site.
- 5 fictional release notes.
- Each story uses changelog format.

## Dot Task Brief

Dot should create/prepare the above as public GitHub repositories, one repo per idea where not already existing. For existing repos, dot should update README files, add MVP issue lists, and ensure the repo is public. For new repos, dot should create the repo, add README, LICENSE, `.gitignore`, and a minimal working scaffold.

## Recommended First Sprint

1. `cronweave` - polish README and working demo.
2. `permission-matrix-studio` - create repo and MVP scaffold.
3. `rtl-ui-stress-tester` - create repo and MVP scaffold.
4. `screenshot-redactor` - create repo and MVP scaffold.
5. `career-evidence-vault` - create repo and MVP scaffold.

## Definition of Done Per Repo

- Public visibility confirmed.
- README includes problem, solution, MVP scope, tech stack, setup, roadmap.
- App runs locally.
- At least one screenshot placeholder or demo section.
- Issues created for MVP tasks.
- No secrets, private company data, or confidential screenshots committed.

_Last updated: 2026-10-10._
