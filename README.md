
Brain Tumor Detection & Architectural Benchmarking

This project focuses on the detection and classification of brain tumors from MRI imaging using three state-of-the-art Deep Learning architectures: ResNet50, VGG16, and Xception. The goal was to compare architectural performance and interpretability using a unified diagnostic dashboard.

📊 Performance Dashboard
I developed a comprehensive Architectural Benchmarking Dashboard in Tableau to move beyond simple aggregate metrics and visualize exactly where each model succeeds or fails.

Interactive Evaluation: Features side-by-side confusion matrices for 1:1 model comparison.

Dynamic Metrics: Utilizes Tableau Calculated Fields to display real-time Accuracy and F1-Scores.

Error Analysis: Standardized color scales highlight specific classification overlaps (e.g., Meningioma vs. Glioma).

🚀 Key Features
Multi-Model Evaluation: Trained and tuned VGG16, Xception, and ResNet50 using transfer learning.

Data Augmentation: Implemented custom rotation, zoom, and lighting adjustment pipelines to ensure model robustness against MRI noise.

Heterogeneous Data Integration: Automated the preprocessing of disparate MRI datasets into a unified TensorFlow tf.data pipeline.

Model Interpretability: Designed a diagnostic interface to evaluate class-specific Precision, Recall, and F1-Scores.

🛠️ Technical Stack
Deep Learning: TensorFlow, Keras

Data Analysis: Python, NumPy, Pandas, Scikit-learn

Visualization: Tableau (Calculated Fields, Heatmaps), Matplotlib

Version Control: GitHub

## Model Performance Dashboard
View the interactive version of the comparison dashboard here: 
https://public.tableau.com/views/braintumorclassification/Dashboard1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
