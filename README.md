# ANIP Benin 2025 — Identity AI System 🪪🤖

## AI-Powered Identity Document Verification
### Finalist — ANIP Benin Challenge 2025

---

## Three Tasks Implemented

### Task 1 — Face Matching & Verification
Siamese Network for facial recognition and 
identity verification on official documents.

**Approach:**
- Contrastive loss function
- Cosine similarity embeddings
- TensorFlow + OpenCV

**Stack:** Python | TensorFlow | OpenCV | NumPy

---

### Task 2 — Age Estimation
Deep learning regression model for age 
estimation from facial photos.

**Results:**
- Best val_MAE: 9.16 years
- Training: 30 epochs with ReduceLROnPlateau
- Dataset: 200 test images

**Stack:** Python | TensorFlow | Transfer Learning

---

### Task 3 — OCR & Document Fraud Detection
Five-class fraud classification on identity 
documents from 4 countries.

**Two versions developed:**
- v1: EfficientNetB0 baseline
- v2 (improved): EfficientNetV2B0 + Cosine Decay
  + Advanced data augmentation

**Results:**
- Best val_accuracy: 20.4% (difficult 5-class problem)
- 200 test images | 4 countries: arizona_dl, esp, est, rus
- CPU-only training

**Stack:** Python | TensorFlow | EfficientNetV2 | OCR

---

## Key Learnings

This challenge demonstrated the complexity of 
real-world biometric AI:
- Face verification requires robust embedding spaces
- Age estimation degrades on small/unbalanced datasets
- Document fraud detection with 5 classes and 
  limited data is genuinely hard

The value lies in the methodology, not just the metrics.

---

## Repository Structure
```
anip-benin-2025-identity-ai/
├── 
│   └── tache1_face_matching.ipynb
├── 
│   └── tache2_age_estimation.ipynb
├── 
│   ├── tache3_ocr_fraud_detection.ipynb (v1)
│   └── tache3_improved.ipynb (v2)
└── README.md
```

## Competition Context
ANIP — Agence Nationale d'Identification des Personnes
Benin | November 2025
Final presentation: Palais des Congrès, Cotonou

## Tache 1 — Detail complet (V2 → V9)

Le repo ci-dessous contient toutes les iterations de la tache 1 :
architectures, diagnostics, corrections, visualisations.

👉 [paseydousow-design/anip-face-matching](https://github.com/paseydousow-design/anip-face-matching)

## Author
Papa Ahmadou Seydou SOW
paseydou.sow@univ-thies.sn
Yaatal Digital — Senegal 🇸🇳

## Other Projects
- [FloodGuardAI](https://github.com/ahmadous/FloodGuardAI)
  WSIS Prizes 2026 | AI for Good Impact Awards 2026
- [Credit Scoring DataTour 2025](https://github.com/ahmadous/credit-scoring-datatour2025)

