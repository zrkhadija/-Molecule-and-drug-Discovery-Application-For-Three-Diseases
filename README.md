# Molecule and drug Discovery Application For Three Diseases
**Main phases that i worked on for this projects:
## Data Preparation

**In this phase, we meticulously handled the data. The key steps involved are:**

1. **Data Import**: We imported the ChEMBL datasets relevant to our three target diseases.
2. **Data Cleaning**: Extensive cleaning was performed to ensure data quality and consistency.
3. **Feature Engineering**: Relevant features were extracted from the datasets to facilitate modeling.

## Modeling Phase

**The modeling phase had two distinct objectives:**

### Molecule Generation

- **We explored two deep learning algorithms: Variational Autoencoder (VAE) and MolGann.**
- **After thorough evaluation, VAE was selected as the preferred algorithm and applied to all three datasets.**

### Bioactivity Prediction

- **We employed various machine learning algorithms to predict two key aspects:**
  - **PIC50 Value and Bioactivity Class**: Predicting the PIC50 value for bioactivit and Classifying compounds based on their bioactivity.
 
- **The best-performing model for each dataset was identified and saved for deployment using Streamlit.**
