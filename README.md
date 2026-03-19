📡 Human Activity Detection using mmWave Radar
📌 Overview

This project focuses on Human Activity Detection using mmWave (millimeter wave) radar signals. The system captures raw radar data, converts it into frequency representations, and uses machine learning to classify different human activities.

The input data is processed into frequency-domain images (PNG format), which are then used to train a model for activity recognition.

🚀 Key Features

📡 mmWave radar-based sensing (no camera required)

🔄 Signal processing from raw data → frequency domain

🖼️ Frequency data converted into PNG images

🤖 Machine Learning model for activity classification

🏃 Detects multiple human activities like:

Jogging

Running

Quenching (or similar motion-based activity)

🧠 How It Works
1. Data Collection

mmWave radar captures motion-based signal data

Raw signals represent movement patterns

2. Signal Processing

Convert raw radar signals into frequency domain

Apply transformations (e.g., FFT) to extract meaningful features

3. Image Generation

Frequency data is converted into PNG images

These images represent motion patterns visually

4. Model Training

Use labeled datasets (Jogging, Running, etc.)

Train a classification model using the generated images

5. Prediction

New radar data → processed → converted to image

Model predicts the human activity


⚙️ Tech Stack

Python

NumPy / SciPy (Signal Processing)

OpenCV / PIL (Image Generation)

Matplotlib (Visualization)

Scikit-learn / TensorFlow / PyTorch (Model Training)

📊 Model Input & Output
Input:

Frequency-domain images (PNG)

Output:

Predicted activity label:

Jogging

Running

Quenching

🛠️ Installation
Dont forgot to install Detectron from respected repo
git clone https://github.com/akashsightspectrum-lab/Human_activity_detection_system.git
cd Human_activity_detection_system
install the requirements diretly from radiowave_detectron.ipynb file

Train Model then
Run Prediction

📈 Future Improvements

Add more activity classes

Improve model accuracy using deep learning (CNNs)

Real-time activity detection

Deploy as an API or edge device solution

🤝 Contribution

Contributions are welcome! Feel free to fork the repo and submit a pull request.


👤 Author

Akash J
📧 jakash2105@gmail.com
