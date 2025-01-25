# Drug Discovery For Tubercolosis using Machine Learning
A brief description of your project and its purpose.  

## **Table of Contents**  
- [Installation](#installation)  
- [Setting Up Conda Environment](#setting-up-conda-environment)  
- [Running the Code](#running-the-code)  
- [Project Structure](#project-structure)  
- [License](#license)  

---

## **Installation**  
Follow these steps to set up the project environment:  

### **1. Install Python 3.9**  
Ensure that Python 3.9 is installed on your system. You can download it from the official Python website:  
[Download Python 3.9](https://www.python.org/downloads/release/python-390/)  

Alternatively, if you prefer using Anaconda, download and install it from:  
[Download Anaconda](https://www.anaconda.com/products/distribution)  

Verify installation:  
```bash
python --version
```
Expected output: `Python 3.9.x`  

---

## **Setting Up Conda Environment**  

1. **Install Conda (if not already installed):**  
   - Download and install Anaconda from the [official website](https://www.anaconda.com/products/distribution).  
   - Verify installation with:  
     ```bash
     conda --version
     ```
     
2. **Create a new environment:**  
   Run the following command to create a Conda environment with Python 3.9:  
   ```bash
   conda create --name my_env python=3.9  
   ```
   
3. **Activate the environment:**  
   ```bash
   conda activate my_env  
   ```

4. **Install dependencies from `requirements.txt`:**  
   ```bash
   pip install -r requirements.txt  
   ```

---

## **Running the Code**  
(Modify this section once the process is finalized.)  

After setting up the environment, you can run the project using the following steps:  

1. Activate the Conda environment:  
   ```bash
   conda activate my_env  
   ```

2. Run the main script:  
   ```bash
   python main.py  
   ```

3. (Optional) Run tests:  
   ```bash
   python -m unittest discover tests  
   ```

---

## **Project Structure**  
```
├── data/                 # Contains datasets  
├── src/                  # Source code  
│   ├── module1.py        # Core logic  
│   ├── module2.py        # Additional functions  
├── tests/                # Unit tests  
├── requirements.txt      # Dependencies  
├── README.md             # Project documentation  
├── main.py               # Entry point of the project  
└── LICENSE               # License file  
```

---

## **License**  
This project is licensed under the [MIT License](LICENSE).  
