# Product name

One sentence: who this is for and what problem it solves.

| | |
|---|---|
| **Team** | Name (@github-handle), role · Name (@github-handle), role · … |
| **Jira board** | https://YOUR-SITE.atlassian.net/jira/software/projects/KEY/boards/1 |
| **Live app** | Added in Class 8 |
| **Stack** | Frontend: … · Backend: … · Database: … · External API: … |
| **Course** | UIU CSE 3422 Software Engineering Laboratory, Fall 2026 |

## Run it locally

List the exact steps a teammate needs on a fresh machine. From Class 8 this becomes one command.

## Run the tests

The exact command(s).

## Project documents

| Document | Where | Due |
|---|---|---|
| Team contract | [docs/team-contract.md](docs/team-contract.md) | Before Class 2 |
| Specification | [docs/specification.md](docs/specification.md) | Draft before Class 3, tag `spec-v1` by Class 4 |
| Proposal slides | `docs/proposal.pdf` | Before Class 4 |
| Design document and ADRs | [docs/design.md](docs/design.md), [docs/adr/](docs/adr/) | Draft before Class 5, tag `design-v1` by Class 6 |
| Test evidence | [docs/test-evidence.md](docs/test-evidence.md) | Class 7 onwards |
| API tests (Postman) | [api-tests/](api-tests/) | Class 7 onwards |
| Usability report | [docs/usability.md](docs/usability.md) | Class 9 |
| Weekly status | [reports/](reports/) | Every week |

## AI use

Say which AI tools the team used, for what, and how you checked the output. Every member must be able to explain every line they submitted.

---

## How this repository grows

This starter gives you the **structure** only. You set up each engineering practice yourselves, after it has been shown in class. By the end of the term your repository is run like a real product.

| You add | Shown in | Due |
|---|---|---|
| This repository (from the template); teammates and the instructor (**@Lazyb0y**) as collaborators | Class 1 | Class 1 homework |
| Jira site and the GitHub for Atlassian connection | Class 1 | Class 1 homework |
| Help-request issue template (`.github/ISSUE_TEMPLATE/`) | Class 1 | Class 1 homework |
| Project-idea issue; the team contract merged through your first pull request | Class 1 | Class 1 homework |
| Licence file | Class 2 | Before Class 3 |
| Branch protection on `main`, pull-request template, `CODEOWNERS`, merge settings, `CONTRIBUTING.md`, `.env.example` | Class 3 | Class 3 homework |
| CI workflow with required checks, Dependabot, secret scanning with push protection, Postman tests in CI | Class 7 | Class 7 homework |
| Docker Compose, deployment on release tags, releases and `CHANGELOG.md` | Class 8 | Class 8 homework |
| CodeQL code scanning, `SECURITY.md`, private vulnerability reporting | Class 10 | Class 10 homework |

**Rule:** don't add a practice before it has been shown in class, unless you already know how it works and can explain it in a viva. Adding something early is allowed, never required, and earns no extra marks. Milestones only check what has already been taught.

## First steps (team lead; delete this section when done)

1. On the template page click **Use this template → Create a new repository**. Owner: your own account. Visibility: **Public**. Name: `cse3422-` and your team name, in lowercase with hyphens (e.g. `cse3422-orbit`); you may rename it to your product name once your idea is approved.
   - **Two repositories** (separate frontend and backend)? Create both from this template. Keep `docs/`, `reports/` and `api-tests/` only in the backend repository, delete them from the frontend one, and link the two READMEs to each other.
   - **One app at the root?** Delete the `frontend/` and `backend/` folders.
2. **Settings → Collaborators:** add every teammate and the instructor (**@Lazyb0y**).
3. Fill in the table at the top of this README. Until your idea is approved, use your team name as the heading.
4. Continue with the Class 1 homework sheet.
