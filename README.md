### GeometricExplanation

---

# From High-Dimensional Chaos to Clear Rules: Post-Hoc Explanations Driven by Geometric Modeling

This is the official code repository for **"From High-Dimensional Chaos to Clear Rules: Post-Hoc Explanations Driven by Geometric Modeling"**. The implementation includes some practical code, where `imageinterpretable.py` is a simple script for image classification (based on ResNet). It can be used to demonstrate the local and global interpretability of the designed method.

---

## Official Code Repository

This is the official code repository for **"From High-Dimensional Chaos to Clear Rules: Post-Hoc Explanations Driven by Geometric Modeling"**. The implementation includes some practical code, where `imageinterpretable.py` is a simple script for image classification (based on ResNet). It can be used to demonstrate the local and global interpretability of the designed method.

---

### Key Features

- **Local Interpretability**: Provides explanations for individual images using spatial heatmaps.
- **Global Interpretability**: Generates fuzzy rules based on feature boundaries (`soft_lower` and `soft_upper`) for key features.
- **Visualization**: Includes visualizations of embedding heatmaps and decision boundaries for critical features.
- **Rule Generation**: Outputs human-readable IF-THEN rules for better understanding of the model's decision-making process.

---

### Usage

To run the code and generate interpretable rules:

1. **Install Dependencies**:
   ```bash
   pip install torch torchvision numpy matplotlib scikit-learn pillow

2. **Run the Scripts**:
   ```bash
   python imageinterpretable.py

3. **Run the Scripts**:
  ```bash
   Output :
   Heatmaps : Saved in the projected_heatmaps folder.
   Fuzzy Rules : Saved in fuzzy_rules.txt.
   Visualization : Rule visualization saved as rule_visualization.png.

