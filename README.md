# AI4CyberSecWorkshop

Welcome to the **AI in Cybersecurity Workshop** repository! This workshop was organized in collaboration with **IEEE ENICarthage University** to introduce participants to the role of **Artificial Intelligence (AI)** in **Cybersecurity**. This repository contains the materials, code, datasets, and presentation slides used during the workshop.
<div style="text-align: center;">
    <img src="resources/1.jpg" alt="FirstSlide" width="800"/>
</div>


---

## Workshop Overview

The **AI in Cybersecurity Workshop** is designed to help participants understand how AI can be leveraged to protect systems from cyber threats. The workshop focuses on two key cybersecurity problems:
1. **Malware Detection**: Using AI to detect malicious software.
2. **Time to Compromise (TTC) Prediction**: Predicting the time it takes for an attacker to breach a system based on system vulnerabilities.

### Key Concepts Covered:
- Introduction to Artificial Intelligence and Machine Learning.
- Understanding classification and regression problems.
- Building and evaluating machine learning models.
- AI-driven approaches for threat detection and prediction.
- Hands-on experience with real-world cybersecurity datasets.

---

## Repository Structure

This repository is organized as follows:

```plaintext
📁 AI4CyberSecWorkshop/
├── 📁 Slides/                   # Contains the slides for the workshop presentation
│   └── AI_in_Cybersecurity_Slides.pdf
│
├── 📁 src/                      # Contains the source code and Jupyter notebooks
│   ├── Malware_Detection.ipynb  # Notebook for the Malware Detection problem
│   ├── Time_to_Compromise.ipynb # Notebook for the Time to Compromise (TTC) problem
│   └── 📁 data/                 # Contains synthetic datasets used in the workshop
│       ├── malware_detection_dataset.csv  # Dataset for malware detection
│       └── time_to_compromise_dataset.csv # Dataset for TTC prediction
│
└── 📄 README.md                 # Information about the workshop and repository
```

### Slides
- The **Slides** folder contains the workshop presentation slides: 
  - [AI in Cybersecurity Slides](./Slides/AI_in_Cybersecurity_Slides.pdf)

### src
- The **src** directory contains the **Jupyter notebooks** and **datasets** used for the hands-on exercises:
  - **Malware Detection**: The `Malware_Detection.ipynb` notebook demonstrates the use of machine learning models to detect malicious software. It uses the `malware_detection_dataset.csv` dataset.
  - **Time to Compromise (TTC) Prediction**: The `Time_to_Compromise.ipynb` notebook focuses on predicting the time it takes for an attacker to compromise a system using regression models. It uses the `time_to_compromise_dataset.csv` dataset.

---


## Getting Started

To get started with the workshop materials, follow these steps:

### 1. Clone the Repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/achrefbenammar404/AI4CyberSecWorkshop.git
cd AI4CyberSecWorkshop
```

### 2. Create a Virtual Environment

Create a virtual environment to isolate the project dependencies:

```bash
# For Linux/Mac
python3 -m venv venv

# For Windows
python -m venv venv
```

### 3. Activate the Virtual Environment

Activate the virtual environment:

```bash
# For Linux/Mac
source venv/bin/activate

# For Windows
venv\Scripts\activate
```

### 4. Install Dependencies

With the virtual environment activated, install the required dependencies using the provided `requirements.txt` file:

```bash
pip install -r requirements.txt
```

### 5. Explore the Notebooks

To follow the hands-on exercises, open the Jupyter notebooks in the `src/` directory.

---
## Datasets

The datasets used in this workshop are synthetic datasets created for educational purposes:
1. **malware_detection_dataset.csv**: Contains labeled data for malware detection tasks.
2. **time_to_compromise_dataset.csv**: Contains data for predicting the time to compromise based on system and network vulnerabilities.

Both datasets are located in the `src/data/` folder.

---

## Workshop Agenda

1. **Introduction to AI and Cybersecurity**:
   - Overview of how AI can enhance cybersecurity and common AI techniques.
   
2. **Supervised Learning in Cybersecurity**:
   - Explanation of classification (malware detection) and regression (time to compromise prediction).
   
3. **Malware Detection**:
   - Using machine learning models (e.g., Random Forest, Logistic Regression) to classify malicious software.

4. **Time to Compromise Prediction**:
   - Building regression models to predict how quickly a system can be compromised based on vulnerabilities and system configurations.

---

## Dependencies

This workshop requires the following Python libraries, which can be installed using the `requirements.txt` file:

- `seaborn==0.13.2`
- `matplotlib==3.8.2`
- `pandas==2.2.0`
- `numpy==1.26.1`
- `scikit-learn==1.4.1.post1`
- `tensorflow==2.16.1`

You can install these dependencies by running:

```bash
pip install -r requirements.txt
```

---

## Contributions

We encourage contributions from participants and the broader community! If you'd like to contribute, feel free to open a pull request with improvements, additional examples, or new exercises.

---

## License

This project is licensed under the MIT License. For more details, see the [LICENSE](LICENSE) file.

---

## Acknowledgments

This workshop is a collaborative effort with **IEEE ENICarthage University**. 
Special thanks to the organizing team.

---

## Contact

For any questions or feedback regarding the workshop, please reach out to us:

- **Workshop Lead**: Achref Ben Ammar - [achref.benammar@enicarthage.edu.tn](mailto:achref.benammar@ieee.org)

