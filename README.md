# Business Organization

Governing documents for **Timeless Way Interactive, LLC**, kept in Markdown so they
version alongside the code. These are copies of the canonical Google Docs; when a
doc changes upstream, re-export it here in the same commit style.

| Document | Source |
| --- | --- |
| [Operating Agreement](Operating-Agreement.md) | [Google Doc](https://docs.google.com/document/d/1Rv1QjxmFArw4-zxytXy1YKWaJrqFZawJkMSfT3OPmw8/edit) |
| [Individual Contributor Agreement](Individual-Contributor-Agreement.md) (Exhibit B) | [Google Doc](https://docs.google.com/document/d/1eQuSVJEfXI5LuzyAmxxYyabqnjKchXgpBFUTQFyUQdk/edit) |
| [Member Perpetual License](Member-Perpetual-License.md) (Exhibit C) | [Google Doc](https://docs.google.com/document/d/1gfziXXNAUx-OGxcYpK_2zhzpN5sSt1uCcNhyrvYqAEY/edit) |
| [Joinder Agreement](Joinder-Agreement.md) | Drafted here — no upstream doc yet |
| [Work Pool Contribution and Assignment](Work-Pool-Contribution-Agreement.md) | Drafted here — no upstream doc yet |
| [Work Pool Acceptance Consent](Work-Pool-Acceptance-Consent.md) | Drafted here — no upstream doc yet |
| [Counsel Questions](Counsel-Questions.md) | Working memo — no upstream doc |

The Operating Agreement is a revised draft and is **not yet executed**. The form
instruments are blank — fill in the blanks per engagement, per Member, or per contribution;
do not edit the templates to record a specific deal.

The Joinder is the instrument the Adoption and Signature page of the Operating Agreement
calls for when a Member is admitted; the Contribution and Assignment is the instrument that
actually moves a project's copyright when it enters the Work Pool under Section 7.2. Both
were drafted here rather than exported from a Google Doc — create the upstream docs and add
the links when they exist.

`Counsel-Questions.md` is different in kind: a working memo, never executed and never
attached to anything. It holds the drafting notes that used to sit inside the three
instruments. They were moved out because several of them record open legal risk in the
Company's own words, and a signed document is the wrong place to keep an admission. Work
each question through with counsel and a CPA, then delete it from the memo.

## [Records/](Records/)

The instruments above are forms. `Records/` holds what actually happened: consents and
minutes, the Section 10.1 registers, and the Work Pool IP manifest.

It is a **separate private repository**
([Business-Records](https://github.com/Timeless-Way-Interactive/Business-Records)), bound
here as a submodule. This repository is public — the governing documents are meant to be
readable by anyone deciding whether to work here — but the records are not: the register
carries Contractors' Thresholds and Unpaid Balances, and the executed instruments carry
signatures. Neither belongs on the open internet. Section 10.2 is how a Member gets a copy:
on request, at the Company's expense.

Cloning this repository without access to that submodule is expected and harmless; `git
submodule update` will simply skip it.
