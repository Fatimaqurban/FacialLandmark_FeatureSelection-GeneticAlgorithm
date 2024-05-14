**Feature Selection Using Genetic Algorithm on RAVDESS Facial Landmark Tracking Dataset**

**Introduction:**
This project implements feature selection using a Genetic Algorithm (GA) on the RAVDESS Facial Landmark Tracking dataset. The goal is to enhance a neural network's classification accuracy for distinguishing between "happy" and "sad" emotions.

**Dataset:**
The RAVDESS dataset comprises 7356 files with 24 professional actors vocalizing expressions across various emotions and intensity levels. For this project, we focused on the "happy" (emotion code 03) and "sad" (emotion code 04) classes, utilizing speech modality (modality code 03).

**Tasks:**

1. **Data Preparation:**
   - Acquire the RAVDESS Facial Landmark Tracking dataset.
   - Extract data entries corresponding to speech modality and emotions "happy" and "sad".

2. **Feature Selection Using Genetic Algorithm:**
   - Implement a Genetic Algorithm for feature selection.
   - Define a chromosome to represent a subset of facial landmarks.
   - Implement selection, crossover, and mutation operators for the GA.
   - Conduct experiments with different configurations of the GA.
   - Evaluate the effectiveness of feature selection in improving classification accuracy.

3. **Documentation:**
   - Explain the chromosome representation and genetic operators used in the GA.
   - Present performance evaluation results for the final model.
   - Analyze the impact of feature selection on model performance and the features selected by the GA.

**Code Implementation:**
The provided code executes the entire process outlined above. It preprocesses the dataset, initializes the GA, defines fitness evaluation, implements selection, crossover, and mutation operations, iterates the GA, and evaluates the final model's accuracy.

**Readme:**
To run the project successfully, follow these steps:
1. Download the RAVDESS Facial Landmark Tracking dataset from [Kaggle](https://www.kaggle.com/datasets/uwrfkaggler/ravdess-facial-landmark-tracking) or [Zenodo](https://zenodo.org/records/3255102).
2. Store the dataset in the appropriate directory.
3. Execute the provided code in a Python environment with necessary dependencies installed (NumPy, pandas, scikit-learn, TensorFlow).
4. Ensure proper configurations for GA parameters such as population size, mutation rate, and termination conditions.
5. Analyze the results and evaluate the impact of feature selection on classification accuracy.

**Dependencies:**
- NumPy
- pandas
- scikit-learn
- TensorFlow

**References:**
- Original dataset: [RAVDESS](https://www.kaggle.com/datasets/uwrfkaggler/ravdess-facial-landmark-tracking)
- Model implementation: [TensorFlow](https://www.tensorflow.org/)
