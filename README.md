# Room Booking

## What this is

Room Booking is a web application designed to help students and teams manage room reservations and avoid double bookings.

## How to run it

You need Python 3.10 or newer.

```bash
python3 -m venv .venv
source .venv/bin/activate          # Windows: .venv\Scripts\activate
pip install -r requirements.txt
uvicorn app.main:app --reload
```

Then open http://127.0.0.1:8000 in your browser. Stop it with `Ctrl+C`.

The entries are kept in memory: after a restart the list is empty again.

## Team

<!-- One row per person: GitHub username and what you mainly take care of.
No real names: this repository is public. -->

| GitHub | Role |
|---|---|
| teolfen | Reviewing (Seat 1) |
| 36rohan | Issues and Project Board (Seat 2) |
| antipacekelvin |Branch Protection and PR Template (Seat 3) |


## How we work

- We create a separate branch for each issue.
- Each pull request is linked to its related issue.
- Every pull request requires approval from another team member.
- Reviewers leave comments on specific lines when reviewing changes.
- The author merges the pull request after approval.
- We update CHANGELOG.md to document project changes.

## Sources

- 2026-11-25: CM104 Assessment 1 instructions and Expert Sheet A, used for understanding the project requirements and review process.

## Use of AI

- 2026-11-25: ChatGPT, used for drafting the pull request review guide and room booking requirements, checked by reading the documentation and reviewing the changes on GitHub.
- 2026-11-25: ChatGPT, used for drafting README sections and providing GitHub workflow guidance, checked against the assignment instructions and GitHub preview.
- 2026-11-26: ChatGPT, used to assist with implementing the booking deletion feature and updating project documentation. The feature was verified locally by adding and deleting room bookings.