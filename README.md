# American Sign Language (ASL) Alphabet Recognition Project

## Overview
This project is meticulously designed to recognize American Sign Language (ASL) alphabet gestures in real-time by leveraging state-of-the-art computer vision and machine learning methodologies. By seamlessly integrating **OpenCV** for webcam functionality, **MediaPipe** for highly accurate and efficient hand tracking, and advanced classification algorithms such as **Support Vector Machine (SVM)** and **Random Forest**, this model can precisely detect ASL hand gestures and seamlessly convert them into their corresponding alphabetic characters, facilitating effective communication for individuals who rely on ASL.

## Features
- **Real-time ASL Alphabet Detection**: Harnesses the power of OpenCV and MediaPipe to efficiently capture, process, and analyze hand gestures through a live webcam feed.
- **Advanced Machine Learning Models**: Utilizes high-performance classifiers such as **SVM** and **Random Forest** to ensure robust and accurate ASL letter recognition.
- **Intuitive Tkinter GUI**: A well-structured and easy-to-navigate graphical user interface is developed using Tkinter, providing real-time visualization of recognized letters while enabling user-friendly control over the system's functionalities.
- **Expanded Recognition**: Supports accurate detection of ASL hand gestures for the **entire English alphabet (A-Z)**, **numerical digits (0-9)**, and a set of commonly used words such as "Hello" and "Thanks," thereby expanding its practical usability.

## Prerequisites
Before proceeding with the installation and execution of this project, ensure that the following dependencies and software requirements are met:

1. **Python 3.13.0** or any later version to support the necessary libraries and modules.
2. **pip** (Python package manager) to handle package installations seamlessly.

To install `pip`, execute the following commands:

**Windows:**
```sh
python -m ensurepip --upgrade
```

**Linux/MacOS:**
```sh
sudo apt install python3-pip
```

### Required Libraries
For optimal performance and smooth execution, install the following essential dependencies by running the command below:
```sh
pip install opencv-python mediapipe numpy scikit-learn matplotlib Pillow mlflow flask
```

## Installation
1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/ASL_Alphabet_Recognition.git
   ```
2. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```
3. **Run the application:**
   ```sh
   python Real_Time.ipynb
   ```

## Usage
1. **Launch the Application**: Open and run the `Real_Time.ipynb` Jupyter Notebook script to initiate real-time ASL alphabet recognition functionality.
2. **Webcam Integration**: Upon activation, the webcam will start capturing input. Present ASL hand gestures in front of the camera, and the model will process the movement, subsequently displaying the recognized character in the GUI.
3. **Text Interaction**: The detected letters will be instantly displayed in real-time within the Tkinter-based graphical interface, providing a seamless ASL-to-text conversion for effective communication.

## Model Training
The model undergoes comprehensive training using carefully extracted hand-tracking data combined with refined gesture classification techniques. Key hand landmarks are analyzed, structured into feature vectors, and subsequently processed through **SVM and Random Forest classifiers**, ensuring highly accurate predictions of corresponding ASL letters.

## Future Enhancements
- **Word Prediction**: Implementing **Generative Adversarial Networks (GANs)** to intelligently predict entire words based on continuous ASL gesture patterns.
- **Cloud Deployment**: Utilizing **Azure AI services** to deploy and scale this system, ensuring efficient real-time ASL recognition accessible from anywhere.
- **AI-Based Recommendations**: Integrating a **personalized recommendation engine** to suggest words or phrases dynamically based on historical user interactions, enhancing the adaptability of the model.

## Contribution Guidelines
Contributions and collaborations are highly encouraged! Whether you wish to enhance functionality, optimize performance, or introduce additional features, feel free to fork the repository, work on feature branches, and submit well-documented pull requests to contribute effectively.

## License
This project is released under the **MIT License**, making it completely open-source. You are free to **use, modify, and distribute** the project under the stated licensing terms.

## Author
Developed and maintained by **[Ahmed Eldkrory]**. For inquiries, contributions, or collaboration opportunities, feel free to connect via **GitHub** or reach out through **email**. We welcome any suggestions or feedback that can help improve the project!

