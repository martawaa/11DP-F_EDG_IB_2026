```mermaid
gantt
   title project timeline:Bioinformatics Analysis of GALES Deficiency Galactosemia
   dataFormat YYYY-MM-DD
   axisFormat %b %d

   section WP1: Setuo & Planing
   T1.1 Reposity setup & Gantt chart creation: Marta Mengxin,  done, t1_1, 2026-09-17, 2026-9-30
   T1.2 Literature search & GALE variant data retrieval :    active, t1_2, 2026-10-01, 2026-10-03
   T1.3 Define analysis scope & pipeline rules (Team):       t1_3, 2026-10-4, 2026-10-06
   Milestone 1: Repositoty & Scope Finalized : milestone, m1, 2026-10-06, 0d

   section WP2: Bioinformatics Analysis
   T2.1 GALE  genomic variant annotation & analysis :         t2_1, 2026-10-06, 2026-10-10
   T2.2 Protein 3D structure & mutation impact modeling        t2_2,2026-10-11, 2026-10-17
   T2.3 Galactose metabolic path way analysis:        t2_3, 2026-10-11,2026-10-17
   Milestone 2: Analysis & Modeling Completed : milestone,m2, 2026-10-17, 0d
   section WP3 :Report & Delivery
   T3.1 Generate & integrate high-res figures:         t3_1, 2026-10-18, 2026-10-21
   T3.2 Draft BMC-style report.md sections    :         t3_2, 2026-10-20, 2026-10-24
   T3.3 Final proofreading, code check & submission (Team) 26-10-24, 2026-10-26
   Milestone 3: Final Project Submission                     :milestone, m3, 2026-10-26, 0d

