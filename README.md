# 

## 🏃‍♂️Running the code
Needed: Google Drive, Google Colab

 1. ⏬ Download the X_train, X_test, y_train, y_test files
 2. ⬆️ Upload X_train, X_test, y_train, y_test to Google Drive
 3. 📖 Open the .ipynb file in Google Colab and run ✅

## Results: 

Below, we show the comparative results of the training and test of the models. The best performing model is LDA (based on the F1 Macro score). The F1 Macro score was chosen for its ability to handle class imbalance

 | Model   | Training Precision | Training Recall | Training F1 Macro | Test Precision | Test Recall | Test F1 Macro |
|:--------|:------------------|:----------------|:------------------|:---------------|:------------|:--------------|
| KNN     | 1.00              | 1.00            | 1.00              | 0.72           | 0.70        | 0.71          |
| RF      | 1.00              | 1.00            | 1.00              | 0.71           | 0.67        | 0.67          |
| **_LDA_** | **_0.98_**          | **_0.98_**        | **_0.98_**          | **_0.76_**       | **_0.77_**    | **_0.76_**      |
| QDA     | 0.99              | 0.99            | 0.99              | 0.70           | 0.70        | 0.69          |

**Table:** Model Comparison Results on Train and Test set
 
### K-Nearest Neighbors
<img width="800" height="450" alt="knn" src="https://github.com/user-attachments/assets/2d85bede-e145-45dc-8317-2ed3b29f9934" />

### Random Forest
<img width="800" height="450" alt="RF" src="https://github.com/user-attachments/assets/b32dba29-5c1c-414c-96ea-f4d3d399cb69" />

### Linear Discriminant Analysis

<img width="800" height="450" alt="lda" src="https://github.com/user-attachments/assets/0d6d57c0-2e91-4f6a-a67d-07f84eb5016e" />

### Quadratic Discriminant Analysis

<img width="800" height="450" alt="qda" src="https://github.com/user-attachments/assets/06578e66-cd2b-40ed-82d8-31e813dbcae5" />

