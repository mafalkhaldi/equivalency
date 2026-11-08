# NavitaEdu Major Finder · مستشار التخصص الجامعي

A free tool from **NavitaEdu** that helps Kuwaiti high school graduates see which university majors their scores can reach, in Kuwait and abroad.

أداة مجانية من **نافيتا** تساعد خريجي الثانوية يعرفون معدلهم المكافئ والتخصصات اللي يوصل لها معدلهم في الكويت وفي البعثات الخارجية.

## How it works · كيف تشتغل

1. **Scores · الدرجات:** high school average, track (science / arts), Math and English aptitude results (English as test %, IELTS or TOEFL).
2. **Destination · الوجهة:** Kuwait universities or MOHE scholarships abroad.
3. **Your rates · المعدلات:** equivalent rates calculated with the official weights for each college or program group.
4. **Programs · التخصصات:** every program with its lowest admitted rate for 2026/27, the student's status (within range / close / below) and the gap.
   - Kuwait University and Abdullah Al Salem University: 111 programs, filtered by university and college.
   - Scholarships abroad: 128 programs in 9 countries, filtered by category and country. Medicine, Dentistry and Pharmacy are sorted by the smallest gap first.
5. **Apply · التقديم** (scholarships abroad only): the student's scores and chosen options are sent to NavitaEdu on WhatsApp.

Available in Arabic and English.

## Data · البيانات

Lowest admitted rates for 2026/27 (239 programs) and the equivalent-GPA weights, from official sources:

- Ministry of Higher Education — Scholarship Plan 2026/27
- Kuwait University — minimum rates and aptitude test weights 2026/27
- Abdullah Al Salem University — admission results 2026/27

The master copy of the data is kept in NavitaEdu's Notion (Admissions → *Minimum Admission Rates 2026/27* and *Aptitude Test Weights 2026/27*).

Results are a guide only. Rates change every year with competition and available seats.

## Technical

- One self-contained file: `index.html` (no build step).
- Hosted on GitHub Pages.
- Can be embedded in another site with an iframe. The page reports its height to the parent page (`navita-calc-height` message) so the frame resizes automatically.

© NavitaEdu
