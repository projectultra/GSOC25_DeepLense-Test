# GSOC 2025 DeepLense Test
---

## Submissions

### 1. **Common Test: Multi-Class Classification**
- **Notebook**: [Common_Test.ipynb](Common%20Test/Common_Test.ipynb)
- **Model Weights**: [Common_Test_Model.pth](Common%20Test/Common_Test_Model.pth)
- **Description**: 
  - Built a multi-class classification model using PyTorch.
  - Evaluated the model using ROC curves and AUC scores.
  - Achieved an AUC score of `0.9542`.

#### ROC Curve for Common Test
![ROC Curve - Common Test](Common%20Test/Common_Test_ROC_Curve.png)

---

### 2. **Specific Test II: Lens Finding**
- **Notebook**: [Specific_Test_Test_II.ipynb](Test%20II/Specific_Test_Test_II.ipynb)
- **Model Weights**: [Test_II_Model.pth](Test%20II/Test_II_Model.pth)
- **Description**: 
  - Developed a binary classification model to identify lenses.
  - Addressed class imbalance using appropriate techniques.
  - Achieved an AUC score of `0.9628` and a final accuracy of `97.2%`.

#### ROC Curve for Specific Test II
![ROC Curve - Specific Test II](Test%20II\Test_II_ROC_Curve.png)

---

### 3. **Specific Test V: Physics-Guided ML**
- **Notebook**: [Specific_Test_Test_V.ipynb](Test%20V/Specific_Test_Test_V.ipynb)
- **Model Weights**: [Test_V_Model.pth](Test%20V/Test_V_Model.pth)
- **Description**: 
  - Implemented a Physics-Informed Neural Network (PINN) incorporating the gravitational lensing equation.
  - Improved performance over the Common Test results.
  - Achieved a validation AUC score of `0.9821`.

#### ROC Curve for Specific Test V
![ROC Curve - Specific Test V](Test%20V\Test_V_ROC_Curve.png)