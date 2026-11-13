# Hesham Ezz — Portfolio

Personal portfolio showcasing **AI automation, custom business web systems, and AV / conference production**.

## Live portfolio
https://heshamezz18.github.io/hesham-ezz-portfolio/

## Featured AI project — ReceiptFlow AI
**Live app (login required):** https://receiptflow-ai-nine.vercel.app/

**Problem:** A client manually photographed receipts, sorted them by month, entered merchant names and amounts, and created spreadsheet reports.

**Approach:** Built a private full-stack receipt-management MVP using:
- **Next.js / React** for the English-language user dashboard
- **Gemini API** to extract merchant, transaction date, paid amount, and currency from images or PDFs
- **Supabase Auth, PostgreSQL, Storage, RLS** for user accounts, transaction records, original images, and access controls
- **Vercel + GitHub** for deployment and source management

**Workflow:** Multi-file upload → Gemini extraction → per-receipt review/correction → approval → encrypted transport to private application storage → filtering and Excel export.

**Implementation status:** Working MVP demonstrated with real receipt tests. The app is private and requires login. Automated Google Sheets sync, exact reproduction of the client's legacy Excel template, and further production hardening remain future work. No customer invoices or API secrets are stored in this public portfolio repository.

## Other work
- AV conference and live-production projects with original media archives on the portfolio site
- Live switching, recording, remote speaker integration, and conference AV operations

## Portfolio structure
- `index.html` — responsive portfolio website with featured software and AV projects
- `Hesham_Ezz_AV_Portfolio.pdf` — AV portfolio
- `Hesham_Ezz_AV_Conference_CV.pdf` — AV-focused CV
- `README.txt` — legacy notes, retained for compatibility

**Contact:** See the public portfolio website for email and LinkedIn.
