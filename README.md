DiagMLLM: Diagnostic Multimodal Large Language Model for Pediatric Abdominal Care

📌 Overview

Accurate diagnostic reporting is essential for pediatric abdominal conditions that often require urgent care. Conventional workflows rely heavily on radiologists’ interpretations, which can introduce variability and delays in treatment decisions.

To address this, we developed DiagMLLM (Diagnostic Multimodal Large Language Model) — a multimodal AI system that integrates imaging and clinical data for automated diagnostic report generation.

🏥 Dataset

DiagMLLM was trained and validated using multi-institutional datasets from:

Seoul National University Hospital (SNUH)

Pusan National University Yangsan Hospital (PNUYH)

Korea University Hospital (KUH)

Data modalities:

Abdominal X-ray

Computed Tomography (CT)

Structured Clinical Records

⚙️ Methodology

CNN Encoder: Extracts features from imaging data (X-ray, CT).

Multilayer Perceptron (MLP): Encodes structured clinical features.

Attention-based Transformer Decoder: Generates diagnostic reports conditioned on fused imaging + clinical representations.

📊 Performance

Validation against expert-written reports showed state-of-the-art performance:

BLEU > 0.95

ROUGE > 0.95

METEOR > 0.95

BERTScore > 0.95

These results demonstrate that DiagMLLM can closely align with expert-level diagnostic reasoning.

🌟 Clinical Impact

Reduces inter-observer variability in radiological interpretation.

Accelerates diagnostic workflows, enabling timely care.

Supports decision-making for pediatric abdominal conditions.
