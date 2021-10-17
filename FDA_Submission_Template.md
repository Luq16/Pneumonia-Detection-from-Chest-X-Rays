# FDA  Submission

**Your Name:** Luqman Awoniyi

**Name of your Device:** Pneumonia detector

## Algorithm Description 

### 1. General Information

**Intended Use Statement:** <br> This algorithm employ Convolutional Neural Network (CNN) model to detect the presence of pneumonia in X-ray images. The aim is to assist radiogist in reviewing X-ray images. 

**Indications for Use:** This algorithm may be used for patient, both male and female withing the age bracket of 1 to 95 whose medical presentation sugested pneumonia. 

**Device Limitations:**
* Infiltration and effusion can confuse this model and lead to false results.
* This algoritm run effeicient on computers with minimum GPU and RAM requirements.

**Clinical Impact of Performance:**

### 2. Algorithm Design and Function

<< Insert Algorithm Flowchart >>

**DICOM Checking Steps:**

**Preprocessing Steps:**

**CNN Architecture:**


### 3. Algorithm Training

**Parameters:**
* Types of augmentation used during training
* Batch size
* Optimizer learning rate
* Layers of pre-existing architecture that were frozen
* Layers of pre-existing architecture that were fine-tuned
* Layers added to pre-existing architecture

<< Insert algorithm training performance visualization >> 

<< Insert P-R curve >>

**Final Threshold and Explanation:**

### 4. Databases
 (For the below, include visualizations as they are useful and relevant)

**Description of Training Dataset:** 


**Description of Validation Dataset:** 


### 5. Ground Truth



### 6. FDA Validation Plan

**Patient Population Description for FDA Validation Dataset:**

**Ground Truth Acquisition Methodology:**

**Algorithm Performance Standard:**
