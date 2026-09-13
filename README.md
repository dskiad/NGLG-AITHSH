# NGLG-AITHSH

Αίτηση Εισδοχής / Υιοθεσίας / Επαναφοράς — a standalone HTML application form.

## Live page

**https://dskiad.github.io/NGLG-AITHSH/**

(Served via GitHub Pages from the `main` branch.)

## Contents

- `index.html` — the application form.

## GDPR / data protection

The form includes a dedicated section (Ενότητα 10) informing applicants how
their personal data is processed and collecting their explicit consent
before submission, covering:

- identity of the data controller (Εθνική Μεγάλη Στοά της Ελλάδος) and the
  submitting Lodge;
- purpose and legal basis of processing (Art. 6 GDPR), including the
  special-category basis for the applicant's self-declarations in Ενότητα 9
  regarding criminal record / disciplinary history (Art. 10 GDPR, Art. 11
  of Greek Law 4624/2019);
- categories of data, recipients, retention period, and security measures;
- the data subject's rights (access, rectification, erasure, restriction,
  objection, portability, withdrawal of consent, and complaint to the
  Hellenic DPA — www.dpa.gr);
- a required consent checkbox (blocks PDF generation until checked) plus a
  separate optional checkbox for the photo.

The form runs entirely client-side — it builds the PDF in the browser and
never transmits data to a server — but the placeholders for the Lodge's own
DPO/contact details in that section should be filled in with the National
Grand Lodge's actual information before the form is put into official use.
This text is a solid starting point, not a substitute for review by the
Lodge's own legal counsel.

## Local preview

Open `index.html` directly in a browser, or serve the folder locally:

```bash
python3 -m http.server
```

Then visit `http://localhost:8000`.
