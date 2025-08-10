
⚠️ **Disclaimer**  
This repository contains demonstration code and synthetic data for AI Ethics PoCs.
It is not production-ready. Unauthorized commercial use is prohibited.

# AI Underwriting Transparency Tool

**Author:** Grimaldi Roberto | AI Ethics  
Explains risk and price decisions with client-friendly narratives and what-if analysis.

## Setup
```bash
pip install -r requirements.txt
streamlit run app.py
```

## Logical Steps
1. Define decision narratives and map to policy reason codes.
2. Train interpretable model (monotonic constraints where relevant).
3. Generate global/local explanations (SHAP/LIME).
4. Build what-if sliders for key inputs; show price impact.
5. A/B test client comprehension; iterate.
6. Auto-generate adverse action letters.
7. Log explanations for audit; retain in CRM.
8. Review quarterly with governance board.

## KPIs
- Business: NPS +10 points; dispute costs ↓.
- Ethics: Parity in pricing deltas across groups.
- Compliance: LPD/GDPR explainability met; auditable logs.

## Files
- `app.py` — Streamlit demo.
- `reports/client_friendly_explanations.md`, `reports/ethics_note.md`
- `assets/cover.png` — cover image placeholder.
