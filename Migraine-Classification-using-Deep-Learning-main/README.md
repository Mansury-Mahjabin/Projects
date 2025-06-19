# Migraine Classification Using Deep Learning

This project focuses on classifying migraine types using a deep learning model. The dataset used in this project contains medical records of users diagnosed with various pathologies associated with migraines.

## Dataset Characteristics

- **Number of Instances**: 400
- **Number of Attributes**: 24
- **Area**: Health
- **Attribute Characteristics**: Real
- **Associated Tasks**: Classification
- **Missing Values**: No

## Data Set Information

The dataset comprises 400 medical records recorded by trained medical personnel at the Centro Materno Infantil de Soledad during the first quarter of 2013. It contains information regarding symptoms or variables of interest required for the classification of migraines.

## Attribute Information

1. **Age**: Patient's age
2. **Duration**: Duration of symptoms in last episode in days
3. **Frequency**: Frequency of episodes per month
4. **Location**: Unilateral or bilateral pain location (None - 0, Unilateral - 1, Bilateral - 2)
5. **Character**: Throbbing or constant pain (None - 0, Throbbing - 1, Constant - 2)
6. **Intensity**: Pain intensity, i.e., mild, medium, or severe (None - 0, Mild - 1, Medium - 2, Severe - 3)
7. **Nausea**: Nauseous feeling (Not - 0, Yes - 1)
8. **Vomit**: Vomiting (Not - 0, Yes - 1)
9. **Phonophobia**: Noise sensitivity (Not - 0, Yes - 1)
10. **Photophobia**: Light sensitivity (Not - 0, Yes - 1)
11. **Visual**: Number of reversible visual symptoms
12. **Sensory**: Number of reversible sensory symptoms
13. **Dysphasia**: Lack of speech coordination (Not - 0, Yes - 1)
14. **Dysarthria**: Disarticulated sounds and words (Not - 0, Yes - 1)
15. **Vertigo**: Dizziness (Not - 0, Yes - 1)
16. **Tinnitus**: Ringing in the ears (Not - 0, Yes - 1)
17. **Hypoacusis**: Hearing loss (Not - 0, Yes - 1)
18. **Diplopia**: Double vision (Not - 0, Yes - 1)
19. **Visual defect**: Simultaneous frontal eye field and nasal field defect in both eyes (Not - 0, Yes - 1)
20. **Ataxia**: Lack of muscle control (Not - 0, Yes - 1)
21. **Conscience**: Jeopardized conscience (Not - 0, Yes - 1)
22. **Paresthesia**: Simultaneous bilateral paresthesia (Not - 0, Yes - 1)
23. **DPF**: Family background (Not - 0, Yes - 1)
24. **Type**: Diagnosis of migraine type (Typical aura with migraine, Migraine without aura, Typical aura without migraine, Familial hemiplegic migraine, Sporadic hemiplegic migraine, Basilar-type aura, Other)

## Project Overview

This project involves building a deep learning model to classify different types of migraines based on the given attributes. The following steps are involved:

1. **Data Preprocessing**: Handling and transforming the data to make it suitable for model training.
2. **Model Building**: Constructing a deep learning model using a neural network architecture.
3. **Hyperparameter Tuning**: Optimizing the model's hyperparameters to achieve the best performance.
4. **Model Training**: Training the model on the dataset.
5. **Evaluation**: Evaluating the model's performance using appropriate metrics.

## Installation

To run this project, you need to have Python installed along with the following libraries:

- TensorFlow / Keras
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
