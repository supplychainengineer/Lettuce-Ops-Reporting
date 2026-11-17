# LettuceOps RCM Reporter

A single-file browser tool that turns each practice's monthly RCM numbers into a branded, Revenue Intelligence report (PDF) for email.

Open `index.html` in any browser. No install, no server. An internet connection is needed for the Download PDF button and the fonts; without it, use Print and choose Save as PDF.

1. **Enter numbers**: pick or add a practice, add the month, type the numbers. Last month's value is shown under each box.
2. **Report**: a cover page, then a story: summary with a Revenue Health Index, performance and contracted future revenue, insurance, cash flow, 12-month outlook, then problems and solutions. Type analyst notes at the foot of any page. Download the PDF and copy the email text.
3. **Branding & products**: company name, colour, logo, footer; the product catalog (what each product does, its best feature, the problems it solves, its link), which the report matches to each practice's findings and features as a spotlight on the last page; per-practice targets and A/R loss-rate assumptions; backup and restore.

**Upload past reports**: on the Enter numbers tab, upload earlier monthly report PDFs (several at once). A built-in reader takes the numbers from the report tables; when the tool is opened inside Claude, Claude also reads the page images, which covers tables stored as pictures and other layouts. Every number is shown for checking, with Claude-read values and disagreements highlighted, before it is saved.

**Payment methods**: each practice has its own list of insurance and patient payment methods (for example Finix, Stripe, CareCredit, EFT), edited in the Payment posting section of the Enter numbers tab. Data entry, the report and the spreadsheet template follow that list. When an uploaded report shows a method the practice does not have yet, it is offered as a new method and added on save.

**Past months by hand**: use "Add earlier month" for one month at a time, or "Add past months from a spreadsheet": copy the 12-month template, fill it in Excel or Google Sheets from earlier reports, and paste it back. Once four or more months have numbers, the report gains a page with 12-month trend charts and a month-by-month table.

**Multiple practices under one owner**: give the practices the same "Group or owner" name on the Enter numbers tab. Each of their reports then gains an "Across your practices" page comparing them for that month, with the group total and what matching the best practice could be worth.

The PDF is built at three times screen resolution with a hidden text layer, so it can be searched and copied from, and product links stay clickable. The Outlook page includes the scoring table behind the Revenue Health Index.

Data is saved in the browser only. Use the backup text to move it between computers.

The outlook shows the "1% better each month" path: exams scheduled, kept rate and conversion each improve by 1% of their own value every month, compounding, with kept rate capped at 97% and conversion at 90%. Starts scale with all three from the trailing three-month average. It is an illustration, not a forecast. Targets and loss rates are editable starting values, not industry benchmarks.

`sample-report.pdf` is the output for the bundled sample (Asana Ortho, October 2026). Patient names are not included; keep them out of this repository.
