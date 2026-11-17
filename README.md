# LettuceOps RCM Reporter

A single-file browser tool that turns the monthly RCM numbers into the client report and a long-term outlook.

Open `index.html` in any browser. No install, no server.

- **Data**: type the month's numbers from the PMS, tracker sheet and payment posting sheet. Use "Add next month" each month. Data is saved in the browser; copy the export text to back it up or move it.
- **Report**: the written summary, the four tables and pre-send checks are generated from the data. Print or save as PDF from here.
- **Outlook**: what the numbers mean over 12 to 36 months. Shows the value of a point of kept-exam rate or conversion, a scenario builder, month signals, and the overdue A/R likely to be lost.

The outlook is a planning model. Starts scale in proportion to exams, kept rate and conversion from the trailing three-month average; production is starts times net production per start. A/R loss rates are editable assumptions.

The bundled sample is Asana Ortho, August to October 2026. Patient names are not included; keep them out of this repository.
