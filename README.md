# NavitaEdu Major Finder · مستشار التخصص الجامعي

A free tool from **NavitaEdu** that helps Kuwaiti high school graduates see which university majors their scores can reach, in Kuwait and abroad.

أداة مجانية من **نافيتا** تساعد خريجي الثانوية يعرفون معدلهم المكافئ والتخصصات اللي يوصل لها معدلهم في الكويت وفي البعثات الخارجية.

## How it works · كيف تشتغل

1. **Scores · الدرجات:** high school average, track (science / arts), Math and English aptitude results (English as test %, IELTS or TOEFL).
2. **Destination · الوجهة:** study in Kuwait or MOHE scholarships abroad. The student goes straight to the programs.
3. **Programs · التخصصات:** the equivalent rates (official weights for each college or program group) sit at the top, then every program with its 2026/27 minimum or lowest admitted rate, the student's status (within range / close / below) and the gap. Lists show 10 programs at a time with "show more".
   - Kuwait University and Abdullah Al Salem University: 111 programs, filtered by university and college.
   - PAAET (التطبيقي): 130 programs (76 boys, 54 girls) with the semester 1 and 2 minimums, filtered by gender and college.
   - Internal scholarships (البعثات الداخلية, Private Universities Council): 87 programs at 12 private universities and colleges, with the minimum % to apply by track.
   - Scholarships abroad: all 148 programs of the MOHE Scholarship Plan 2026/27 in 9 countries, filtered by category and country, with the plan's minimum high-school % to apply. 128 also show the lowest admitted rate; arts-track students see the 9 programs open to them. Medicine, Dentistry and Pharmacy are sorted by the smallest gap first.
4. **Apply · التقديم** (scholarships abroad only): the student's scores and chosen options are sent to NavitaEdu on WhatsApp. The orange «ابي اقدم» button at the top of the abroad programs opens WhatsApp directly.

Available in Arabic and English.

## Data · البيانات

Programs, minimums and lowest admitted rates for 2026/27, and the equivalent-GPA weights, from official sources:

- Ministry of Higher Education — Scholarship Plan 2026/27 (148 programs and minimum % to apply) and lowest admitted rates 2026/27
- Kuwait University — minimum rates and aptitude test weights 2026/27
- Abdullah Al Salem University — admission results 2026/27
- PAAET — minimum admission rates 2026/27 (boys and girls)
- Private Universities Council — internal scholarship plan, semester 1 2026/27 (official posters, 30 June 2026)

The master copy of the data is kept in NavitaEdu's Notion (Admissions → *Minimum Admission Rates 2026/27*, *MOHE Scholarship Plan 2026/27* and *Aptitude Test Weights 2026/27*).

Results are a guide only. Rates change every year with competition and available seats.

## Brand

Navita brand identity (NavitaEdu Notion → Social Media Playbook → Canva notes): navy #1A3659 leads, orange #EA692D for buttons and key numbers; Cairo for Arabic, Inter for English headings, Poppins for English text. Official white logo with the orange torch, unchanged.

## Technical

- One self-contained file: `index.html` (no build step).
- Hosted on GitHub Pages.
- Can be embedded in another site with an iframe. The page reports its height to the parent page (`navita-calc-height` message) so the frame resizes automatically.

© NavitaEdu
