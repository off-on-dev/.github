# OffOn.dev Governance

This document defines how OffOn.dev is governed. It applies to every repository
in the `off-on-dev` GitHub organization and to the offon.dev project as a whole.

## Model

OffOn.dev is **founder-led**: a single **Project Lead** holds final
decision-making authority, supported and advised by a **Governance Committee**.
The model exists to serve the community while guaranteeing one thing above all —
**the project cannot be captured or controlled by any single company.** Over
time, the Lead intends to transfer authority to the Governance Committee or a
neutral foundation (§5).

---

## 1. Roles

### 1.1 Project Lead

The Project Lead is **David Hirsch** *(@DavidPHirsch)*.

The Lead serves in a **personal capacity**. No employer of the Lead — or of any
Committee member — acquires any right of control over the project by virtue of
that employment. The project is independent of the Lead's employer.

The Lead holds these **reserved powers**, which are not delegated:

- Final decision (and veto) on direction, scope, and roadmap.
- Any **change of license**, and any decision to **close, archive, or sunset** a
  project or the organization.
- Control of the **OffOn name and logo**, the **offon.dev domain**, the project
  **infrastructure**.
- **Composition of the Governance Committee** — appointment and removal of members.
- Amendment of this document (see §6).

The Lead is expected to consult the Governance Committee before significant
decisions and to act in the interest of the project — but retains the final word.

### 1.2 Governance Committee (GC)

The GC advises the Lead, carries delegated authority over day-to-day project
matters, and is the body to which the Lead may eventually transfer control (§5).

- **Size:** up to **5** members in addition to the Lead. *(tune)*
- **Capacity:** members serve as **individuals**, not as representatives of any
  employer.
- **Delegated scope:** maintainer appointments, roadmap and proposal review,
  Code of Conduct enforcement decisions, and any matter the Lead delegates.
- **Decisions:** by lazy consensus; where a vote is needed, by **simple majority**
  of the GC. The **Lead holds a casting vote and a veto**. Reserved powers (§1.1)
  are never subject to GC vote.
- **Meetings:** at least **quarterly**, plus as needed; decisions and rationale
  are recorded publicly.

### 1.3 Maintainers

Maintainers have merge rights in one or more repositories. They are proposed by
existing maintainers or the GC and confirmed by the Lead or GC. Maintainers are
listed in `MAINTAINERS.md`.

### 1.4 Contributors

Anyone who submits a contribution under the DCO (§4). Contributors retain
copyright in their contributions.

---

## 2. Joining the Governance Committee (selection)

Membership is **earned and invited**, not bought or assigned.

1. **Eligibility:** sustained, constructive contribution to the project
   (code, content, community, or operations) over a meaningful period, and
   alignment with the project's values.
2. **Nomination:** any GC member, maintainer, or the Lead may nominate a
   candidate; candidates may also self-nominate. Nominations state the
   candidate's contributions and current employer/affiliation.
3. **Review:** the GC reviews the nomination against the eligibility criteria
   and the corporate-neutrality limits (§3).
4. **Appointment:** the **Lead appoints** members. (This is a reserved power.)
5. **Term:** **2 years**, renewable, ideally staggered so seats don't all turn
   over at once. *(tune)*
6. **Stepping down / removal:** a member may resign at any time. The Lead may
   remove a member; the GC may recommend removal for cause (inactivity, CoC
   violation, or a neutrality breach under §3) by majority.

---

## 3. Corporate neutrality (anti-capture)

These rules are the core protection against any one company taking control:

- **Individuals, not companies.** Seats belong to people, not employers, and do
  not transfer with a job change.
- **Disclosure.** Members disclose their employer and any material affiliation,
  and keep it current.
- **Per-employer cap.** No more than **one (1)** GC seat (excluding the Lead) may
  be held by people sharing the same employer. *(tune)*
- **No company majority.** Employees of for-profit companies must never hold a
  majority of GC seats. If affiliations shift so that they would, the
  most-recently-appointed conflicting member(s) recuse or step down until the
  balance is restored.
- **Recusal.** Members recuse themselves from decisions where their employer has
  a material interest.
- **No purchase of influence.** Committee seats, the Lead role, the trademark,
  the domain, and the infrastructure are never for sale or transfer to a company.
- **Sponsorship ≠ control.** Financial sponsorship grants recognition only —
  never a seat, a vote, or any decision right.

---

## 4. Contributions and intellectual property

- OffOn.dev uses the **Developer Certificate of Origin (DCO)**. Every commit is
  signed off (`git commit -s`). See `CONTRIBUTING.md`.
- The project will **not** adopt a Contributor License Agreement that assigns or
  exclusively licenses contributors' copyright to any single entity.
- **Inbound = outbound:** contributions are accepted under the license of the
  repository they are submitted to.
- Because copyright stays **distributed across contributors**, no single party —
  including a future owner — can unilaterally relicense or close already-released
  open-source code.

---

## 5. Succession and transition

The Lead intends, over time, to transfer control to the Governance Committee
(operating as an elected steering council) or to a **neutral nonprofit
foundation**. The intent is that the project outlives any individual and can
never be acquired by a company.

- **Planned transfer.** The Lead may, at any time, transfer the reserved powers
  and assets — **trademark, domain, infrastructure, repositories, and funds** —
  to (a) the GC as an elected council, or (b) a neutral foundation. Candidate
  homes include The Commons Conservancy, Linux Foundation Europe, the Software
  Freedom Conservancy, or an Austrian gemeinnütziger Verein. *(choose later)*
- **Continuity / bus factor.** If the Lead is unreachable for **90 days**, the GC
  by a two-thirds vote appoints an **interim Lead** and begins transition to a
  foundation or elected council within **6 months**. *(tune)*
- **Irrevocability.** Once assets are donated to a neutral foundation, the
  transfer is **permanent** — this is the point at which the project becomes
  un-closable by anyone, including a future Lead.

---

## 6. Amendments

While the Lead role is held, the Lead may amend this document after consulting
the GC.

**Protected principles** — the corporate-neutrality rules (§3), the DCO /
no-assignment-CLA commitment (§4), and the irrevocability of a foundation
transfer (§5) — are intended as the project's permanent floor.

> **Entrenchment option (your call):** the Lead may commit that the Protected
> Principles can only ever be strengthened, never weakened, while the Lead role
> is held — making the anti-capture guarantees binding even on a future Lead.
> If you want this, keep this paragraph; if you prefer to retain full amendment
> freedom for now, delete it.

---

*OffOn.dev is community-run and vendor-neutral. The OffOn name and logo are
reserved; see `TRADEMARK.md`.*
