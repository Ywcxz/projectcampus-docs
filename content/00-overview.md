# Overview

*What CAMPUS is, where it stands, and how to read this document*

CAMPUS (Connecting All Members, Places, and University Services) is a student-first proposal for Visayas State University. It imagines a digital layer over the physical university that connects students with the people, organizations, knowledge, places, services, and opportunities they need, designed around VSU's own culture, values, policies, geography, and people. It complements VSU's systems and DIGITS rather than offering an alternative to them. It is not a commercial product and not a plan for Philippine higher education in general. [Established] (D-001; D-029; D-183)

By the author's observation, when a student asks about a scholarship, a grade, or enrollment in one of VSU's community groups on Facebook, the reply that comes most often is some version of "go to USSO." [Unresolved] (P-03) The advice is usually right: the University Student Services Office handles scholarships, student housing, and the recognition of organizations. [Established] (E-058; [Chapter 2.3](02c-network-fit.md)) But a reply can't say which window, what to bring, whether the office has already answered the same question, or whether that answer still holds. [Proposed] CAMPUS starts there: a receptionist that points students to answers people at VSU have already written, each with its source and date, and to the right office when none exists yet. [Proposed] (D-178, D-181)

## Where it stands, November 2026

- CAMPUS is an independent project led full-time by one person, Leo M. Subingsubing, a VSU Main Campus alumnus, as a passion project. There is no team, partner, or institutional collaboration. [Established] (D-001)
- No VSU office has reviewed, endorsed, approved, funded, or adopted CAMPUS. When this document refers to VSU's plans, systems, or goals, it implies none of these. [Established] (D-016; [Chapter 12](12-roadmap.md))
- CAMPUS proposes one product, the social/academic network, with the campus intranet as its long-term infrastructure. [Established] (D-098) Hop-It, now a later module of the network, keeps its Alpha PRD and functional specification of late September 2026. [Established] (D-027; D-098)
- CAMPUS builds first and learns from use. The first build is the network's first place, seeded with real public information, such as the Citizen's Charter and VSU's service pages, and with made-up members labeled as made up, with a receptionist at its door. [Established] (D-178) The receptionist writes no answers of its own, and its first version is plain search. [Established] (D-181) Its code will live in a repository of its own, private until its licence and the commercial path are settled. [Established] (D-179, D-184; Q-77)
- A second build, one learning simulation for one Mechanical Engineering course, is deferred and may be taken up later; learning is outside this proposal for now. [Proposed] (D-190)
- No field research has been run yet, so every problem CAMPUS addresses is still a hypothesis. [Established] (D-083; D-114) The survey, the interviews, and the study of office workflows follow the builds and run when a VSU decision needs them. [Established] (D-178)

## The structure

```text svg=campus-structure
CAMPUS ──complements──► VSU's systems and DIGITS
a student-first digital     how CAMPUS relates to DIGITS
layer over the physical     is VSU's to decide
university
   │
   ├──proposes──► Social/academic network   the one product;
   │                 │                      its first place is the first build
   │                 ├──► Later modules     marketplace · Housing · Hop-It's
   │                 │                      delivery, each waiting for its
   │                 │                      own evidence
   │                 └──► Campus intranet   long-term infrastructure,
   │                                        a direction only
   ├──► Digital twin       research only; its first step, places and
   │                       an office guide, proposed
   └──► Later directions   not commitments
```

[Established] (D-017; D-079; D-081; D-098; D-178; D-183)

| Part | What it is | Status |
| --- | --- | --- |
| [CAMPUS](01-campus.md) | The umbrella vision: a digital layer over the physical university | Proposed |
| [Social/academic network](02-social-network.md) | The one product CAMPUS proposes: VSU's own alternative to Facebook for campus life, with discussions, groups, and student services, designed and governed for the university and free of ads and endless feeds. The marketplace, Housing, and Hop-It's delivery are its later modules | Proposed; leads the first pitch; its first place is the first build |
| [Digital twin](03-digital-twin.md) | A living model of the campus and what happens in it: possibly the largest project of all and the university's long-term aspiration, starting from finding places and knowing which office handles what | Research only; first step proposed |
| [Campus intranet](04-intranet.md) | The long-term backbone: local-first infrastructure, offered as a direction for VSU ICT and DIGITS, not an immediate ask | Direction only |
| [Later directions](06-later-directions.md) | High-school-to-college bridging, learning record, research discovery, analytics and AI | Not commitments |

## What comes next

This document is the reference, in the way a thesis is: it holds the content, the sources, and the record of decisions. Most people will meet CAMPUS through what is built from it: a concept note, and an interactive site for students, faculty, staff, and administration that is also the pitch. [Established] (D-082, D-151)

What gets made comes in this order. [Established] (D-178; [Chapter 12](12-roadmap.md)) First, the network's first place with its receptionist, the first thing people can use. Alongside it, the concept note, two pages printed with a PDF of the same text, tried first on readers the author trusts [Established] (D-095, D-100); the interactive site, built now with placeholders where VSU evidence is still missing [Established] (D-084); and the survey site, built and kept closed until VSU's written permission is in hand. [Established] (D-039, D-114) Then the author goes to OVPSAS, the Office of the Vice President for Student Affairs and Services, in person, with the first place, the concept note, and the interactive site, and with two separate asks: permission to run the student survey and the interviews, and interest in CAMPUS. [Established] (D-083, D-178) OVPSAS comes first because the network serves students above all through the services that office oversees. [Proposed] (D-024; D-183) Field research follows, and the interactive site is presented again, with findings in place of placeholders, instead of pitch slides. [Established] (D-151) Students see the interactive site only after they have answered the survey. [Established] (D-084)

## How to read this document

Every significant claim carries one of three tags:

- [Established] means supported by documents, completed work, or a recorded decision.
- [Proposed] means a design idea or hypothesis that has not been validated.
- [Unresolved] means an open question, or a claim nobody has verified yet.

A small raised number at the end of a claim, just before its tag, as in a thesis, names the claim's source: click it to open the source itself in a new tab, or hover to see the full reference. Every source is also listed, numbered, in the References at the end of the chapter. A claim with no number rests on the text around it or on the chapter's Sources.

Sources are kept apart by type as well: official information, community knowledge, opinion, unverified information, scholarly work, and external sources ([Chapter 9](09-governance.md)). The evidence behind the main claims is listed in the [evidence register](08-evidence.md), each item linked to its source, rated for confidence, and dated when its source is checked. Decisions are recorded in one place, the [decision register](13-decisions.md). A decision made in a conversation or a draft counts only once it is entered there.

## What changed from v0.1

Version 0.1, committed on 22 September 2026, was a 55,776-word R&D blueprint plus an 18-chapter site that restated it in about 19,300 words. Version 0.2 reorganized everything around the product structure and first cut the text to about 11,700 words. Rewriting the chapters in depth has since made it several times longer, which is why it now serves as the reference rather than the read (D-082). Nothing is lost: v0.1 sits unchanged in the [archive](https://github.com/Ywcxz/projectcampus-docs/tree/main/archive/v0.1), and chapters cite its sections where detail helps. Every change of direction since then is recorded in the decision register, starting at D-021.

> **Not affiliated.** Project CAMPUS is not officially affiliated with Visayas State University.
