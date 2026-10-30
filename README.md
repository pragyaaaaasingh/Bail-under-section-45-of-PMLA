# Bail-under-section-45-

Bail under Section 45 of the Prevention of Money Laundering Act, 2002 in the Supreme Court of India, 2021 to 2026

## Team
- Ashish Tanmay, Section A 23010421134
- Pragya, Section A PRN- 23010421035

## Topic
This project examines reasoned judgments of the Supreme Court of India deciding regular bail, anticipatory bail, and arrest-legality challenges under Section 45 and Section 19 of the Prevention of Money Laundering Act, 2002 (PMLA) between 1 September 2021 and 31 August 2026. Section 45(1) imposes stringent twin conditions requiring an accused to establish reasonable grounds to believe that they are not guilty of the offence and are not likely to commit any offence while on bail. The topic interests our team because the five-year period captures a profound doctrinal oscillation: from the three-judge bench in *Vijay Madanlal Choudhary* (2022) upholding the revived twin conditions, to the 2024–2026 jurisprudence subordinating statutory stringency to the fundamental right to a speedy trial under Article 21 of the Constitution.

## How we found the judgments
We searched the official Supreme Court of India portal (`sci.gov.in` and Digital SCR / e-SCR) alongside Indian Kanoon using the Boolean queries `"Section 45" AND "Prevention of Money Laundering Act" AND "bail"` and `"Directorate of Enforcement" AND "Section 45" AND "INSC"` filtered between `01-09-2021` and `31-08-2026`. The initial search yielded 68 orders and judgments. Following the assignment protocol, we excluded summary Special Leave Petition (SLP) dismissals, unreasoned interim bail extensions, medical bail orders lacking doctrinal analysis, and judgments dealing purely with Section 5 attachment or Section 197 CrPC sanction (*Bibhu Prasad Acharya*). We retained 18 reportable, reasoned judgments carrying neutral `INSC` citations where the Supreme Court directly adjudicated bail thresholds or custodial release under the PMLA.

## What the data shows

![Judgments per year](chart1-per-year.png)

The first chart tracks the annual distribution of reasoned PMLA bail judgments from 2021 to 2026. Activity peaked in 2023 (8 judgments) and 2024 (6 judgments), driven by high-profile enforcement actions and immediate doctrinal disputes following *Vijay Madanlal Choudhary v. Union of India* (`2022 INSC 757`). What surprised us most was the sharp contrast in doctrinal direction between the two peak years: while 7 of the 8 judgments in 2023 enforced strict statutory compliance in favour of the Directorate of Enforcement—culminating in *Tarun Kumar* (`2023 INSC 1006`) and *Saumya Chaurasia* (`2023 INSC 1073`)—5 of the 6 judgments in 2024 granted relief to individual accused by invoking procedural guardrails and Article 21.

![Outcomes of appeals](chart2-outcomes.png)

The second chart displays the formal procedural outcomes across the 18 judgments: 11 appeals were `Allowed` (61.1%) and 7 were `Dismissed` (38.9%), with zero partly allowed orders. At first glance, an 11-to-7 allowance rate suggests a court overwhelmingly inclined to grant bail. However, cross-tabulating `Outcome` against `Who brought the case` revealed a critical nuance that did not immediately appear in raw outcome counts: 3 of the 11 `Allowed` appeals (*M. Gopal Reddy*, *Aditya Tripathi*, and *Kanhaiya Prasad*) were filed by the Directorate of Enforcement to cancel bail orders passed by High Courts that had failed to record satisfaction under Section 45.

![Winning party comparison](chart3-who-won.png)

The third chart isolates the substantive prevailing party (`Who won`) across the five-year dataset, showing that the `State or public body` won 10 cases (55.6%) while the `Individual` accused won 8 cases (44.4%). What stood out is the chronological bifurcation of these victories. From July 2022 to March 2024, the State won 8 out of 9 cases (88.9%), losing only in *Pankaj Bansal* (`2023 INSC 866`) where the Directorate failed to furnish written grounds of arrest under Section 19(1). Conversely, from May 2024 to January 2026, individual accused won 7 out of 8 cases (87.5%), anchored by *Manish Sisodia* (`2024 INSC 595`), *Prem Prakash* (`2024 INSC 637`), *V. Senthil Balaji* (`2024 INSC 739`), *Udhaw Singh* (`2025 INSC 247`), and *Arvind Dham* (`2026 INSC 12`).

## Limits
A reader should not conclude from these 18 reasoned judgments that nearly half of all PMLA undertrials secure bail before the Supreme Court. This dataset excludes hundreds of unreasoned dismissal orders at the SLP notice stage and reflects only contested appellate litigation involving substantial constitutional questions or prolonged custody exceeding 14 months. Furthermore, as *Union of India v. Kanhaiya Prasad* (`2025 INSC 210`) confirms, where custody is short and trial delay is not established, the twin conditions under Section 45 remain mandatory and binding on all trial courts and High Courts.

## AI-use disclosure
We used Google Gemini Pro to assist in structuring the HTML visualization dashboard (`index.html`), writing Chart.js rendering scripts, and cross-checking neutral `INSC` citation numbers. We did not rely on AI summaries or headnotes to code the dataset. Every judgment's full PDF was downloaded from the official Supreme Court portal (`sci.gov.in`), read by the assigned team member listed in the `Coded by` column, and verified against the original judgment text for exact bench strength, decision date, statutory provision, issue, holding, and primary precedent.
