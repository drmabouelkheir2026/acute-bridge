# AcuteBridge — SMART-REF V7.1 Assessor Edition

AcuteBridge is a clinician-first referral interface for the SMART-REF V7.1 workflow. The hosted assessor edition uses **synthetic, non-identifiable demonstration data** so reviewers can navigate the full workflow safely.

## Assessor walkthrough

Open the website and choose **Start guided demo**. The walkthrough covers:

Dashboard → Create Referral → Pending ED Approval → Acute Medicine → Governance Audit

The **Accepted** and **Redirected** dashboard cards are clickable and open the corresponding filtered audit history.

## Clinical workflow

ED structured referral → grounded AI copy-edit/SBAR draft → mandatory ED human approval → mandatory Acute Medicine decision → append-only governance audit.

## Backend contract

The visible UI brand is **AcuteBridge**, while the technical backend remains **SMART-REF V7.1**. The existing n8n webhook names and the SMART_REF_LIVE / SMART_REF_AUDIT data-table contracts are not renamed by this frontend.

## Safety

The public assessor interface uses only synthetic or non-identifiable data. It is a prototype/assessment interface and does not represent production clinical deployment, local information-governance approval, or NHS endorsement.

## GitHub Pages

This repository includes a Pages deployment workflow. If GitHub requests it, go to **Settings → Pages** and set **Source** to **GitHub Actions**.