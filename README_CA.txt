California Add‑On Pack — Trucking Intelligence AI
=================================================

Upload the following to your repo ROOT (asarhangian.github.io) and commit:
- ca.html
- drayage.html
- sitemap.xml (overwrite your old one so these pages are indexed)
- templates/ctc_tests_template.csv
- templates/drayage_units_template.csv
- templates/ab5_risk_template.csv
- templates/incentives_pipeline_template.csv

Add nav links (one-time, 30 seconds):
- In index.html (and any other pages you care about), add two links into the nav:
  <a class="link" href="ca.html">California</a>
  <a class="link" href="drayage.html">Drayage</a>

What’s included:
- ca.html → CA Edition page with a localStorage Clean Truck Check tracker + links to templates
- drayage.html → Drayage-specific checklist and templates
- templates/*.csv → ready-to-send sheets for your Ops Tune-Up
- sitemap.xml → includes ca.html and drayage.html so Google finds them

Tip: If the new nav links don't show, hard refresh (Cmd+Shift+R / Ctrl+F5).
