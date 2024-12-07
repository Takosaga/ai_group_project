# **YOLOv8 Model Training, Validation, and Testing Report**

---

## **Step 1: Data Preparation**
### Objective
Prepare labeled data for training, validation, and testing the YOLOv8 model.

### Tasks
- Raw data collected and uploaded to **Google Cloud Platform (GCP)**.
- Manual annotation of a subset of data using **CVAT**, focusing on three classes:
  - **Passenger Vehicles (V)**  
  - **Cargo Vehicles (C)**  
  - **Buses (S)**  
- Labeled data split into:
  - **Train**: 60%
  - **Validation (Val)**: 20%
  - **Test**: 20%
- Data formatted to YOLO-compatible structure:
  - `images/` and `.txt` annotation files.

---

## **Step 2: Model Training**
### Objective
Train YOLOv8 to detect three classes (V, C, S) using labeled data.

### Process
- Pre-trained YOLOv8 weights were loaded for transfer learning.
- Training conducted with the following parameters:
  - **Epochs**: 50  
  - **Image Size**: 640x640  
  - **Batch Size**: 16  
  - **Optimizer**: AdamW  
- Intermediate results saved to GCP during training.

### Outcome
- Trained model (`best.pt`) saved for further evaluation.

---

## **Step 3: Validation**
### Objective
Validate the trained YOLOv8 model on the validation dataset to ensure generalization.

### Process
- The `val` dataset was used to calculate metrics:
  - **Precision**  
  - **Recall**  
  - **mAP@0.5**  
  - **mAP@0.5:0.95**  
- Metrics displayed in the notebook and saved as part of the validation output.

### Outcome
Validation confirmed the model's ability to generalize, with **mAP@0.5 exceeding 80%** across classes.

---

## **Step 4: Testing on Labeled Data**
### Objective
Evaluate the trained model on the `test` set to assess real-world performance.

### Process
- Predictions generated for the `test` dataset.
