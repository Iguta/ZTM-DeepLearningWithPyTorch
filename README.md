# 🧠 Zero To Mastery PyTorch Deep Learning Bootcamp

Welcome to my personal learning hub and code playground for the **"PyTorch for Deep Learning: Zero to Mastery"** bootcamp on Udemy, taught by [Andrei Neagoie](https://twitter.com/andreineagoie) and [Daniel Bourke](https://twitter.com/mrdbourke).

---

## 🎯 Project Goal

This repository is designed to:

- 📘 Systematically learn Deep Learning with PyTorch from the ground up.
- 🧪 Implement and experiment with code examples, exercises, and projects from the bootcamp.
- 🧾 Track my progress and document key learnings, challenges, and solutions.
- 📂 Build a portfolio of PyTorch-based projects showcasing various models and techniques.

---

## 📚 Course Information

- **Course Title**: PyTorch for Deep Learning: Zero to Mastery  
- **Platform**: Udemy  
- **Instructors**: Andrei Neagoie & Daniel Bourke  
- **Course Link**: *https://www.udemy.com/share/107tsS3@1LOtnUVRucBexD5ee74DHx_O2MCC0ocKvfunZvCDZfF6XDbtCPxttOmoaiI9XYQWjQ==/*

---

## 📂 Repository Structure


---

## 🧠 Workflow & Learning Approach

For each major section, I will:

- **Understand Concepts**: Learn the theoretical foundations of PyTorch and deep learning.
- **Code Along**: Implement course examples and follow instructor-led coding.
- **Experiment**: Tweak code, try new architectures, play with hyperparameters and datasets.
- **Document**: Capture insights, take notes, and update both notebooks and this README.

---

## 📈 My Learning Progress

> I will update this section as I complete each section of the course.

### ✅ Section 0: PyTorch Fundamentals – *Completed on [Date]*  
**Key Learnings**: Tensors, tensor operations, GPU acceleration, `torch.autograd`

### 🔄 Section 1: PyTorch Workflow – *In Progress*  
**Key Learnings**: Building models, training loop, loss functions, optimizers, evaluation metrics

<!-- Add more sections as progress continues -->

---

## 🔍 Key Insights

> A collection of practical learnings, tips, and "aha!" moments.

- Using `torch.no_grad()` during evaluation reduces memory usage and speeds up inference.
- Difference between `model.train()` and `model.eval()` — critical for layers like Dropout and BatchNorm.
- Saving model state_dict vs. entire model for better portability and flexibility.

---

## 🛠️ Technologies Used

- **Python**
- **PyTorch** – Core deep learning framework
- **NumPy** – Efficient numerical computing
- **Pandas** – Data manipulation and analysis
- **Matplotlib** / **Seaborn** – Data visualization
- **Scikit-learn** – Metrics, preprocessing, traditional ML tools
- **Google Colab** – Cloud-based GPU-powered notebook environment
- **Git & GitHub** – Version control and collaboration

---

## 🔧 Installation

To run notebooks locally:

```bash
# (Optional but recommended) Create a virtual environment:
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install required packages:
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
