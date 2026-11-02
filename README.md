<h1 align="center">Satvik Jain</h1>
<p align="center">ML engineer. Python, PyTorch, and tools that make ML code more trustworthy.</p>

<p align="center">
  <a href="https://www.linkedin.com/in/satvik-jain-profile/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://satvikjain.com/"><img src="https://img.shields.io/badge/Portfolio-FF5722?style=flat&logo=google-chrome&logoColor=white" alt="Portfolio"></a>
  <a href="mailto:satvik.jain.kht@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

## Featured: trainlint

An offline checker for ML training code, plus agent skills that steer coding agents away from the
same mistakes. It flags bugs that run without errors: preprocessing fitted before the split, eval
mode left on, softmax before `CrossEntropyLoss`, swapped `y_true` and `y_pred`, and more.

<p align="center">
  <a href="https://github.com/Satvik-jain/trainlint">
    <img src="https://raw.githubusercontent.com/Satvik-jain/trainlint/main/assets/demo.gif" alt="trainlint demo: 85% accuracy on random labels with a leak, 48% after the fix" width="720">
  </a>
</p>

```console
uvx trainlint check train.py
