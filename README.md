# 📘 CKA & CKAD Practice Labs

![GitHub](https://img.shields.io/github/license/ibtisam-iq/cka-ckad-practice-labs)
![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen)

A hands-on **open lab of Kubernetes practice questions and solutions**, curated during my preparation for the **Certified Kubernetes Administrator (CKA)** and **Certified Kubernetes Application Developer (CKAD)** exams. This repository is designed to help every Kubernetes learner succeed.

---

## 🎯 Why This Repository Exists

The core purpose is **to serve the community**. Preparing for CKA/CKAD involves solving tricky, exam-like scenarios under time pressure. I created this lab to share **real questions, outputs, and explanations**, reducing the struggle for future candidates.

💡 *If you sincerely practice these questions and understand the explanations, you’ll be well-prepared to pass the exams.*

---

## 🔑 How I Prepared

I prepared for **CKA and CKAD in parallel**, using:

* **KodeKloud** courses and labs
* **KillerCoda** scenarios
* **Killer.sh** (official simulator)
* **Udemy** practice material
* **YouTube** tutorials
* **ChatGPT** (for concept breakdowns and alternate perspectives)

For simple tasks, I practiced without recording. For complex tasks, I documented:

* The **original question statement**
* **Shell commands & outputs**
* **Detailed explanations** (with exam tips and gotchas)

---

## 🗂 Repository Structure

The repository is organized **topic-wise**:

```
📂 cka-ckad-practice-lab
 ┣ 📂 deployments
 ┃ ┗ deployments.md     # Deployment-related questions + solutions
 ┣ 📂 networking
 ┃ ┗ networking.md      # Networking-related practice
 ┣ 📂 storage
 ┃ ┗ storage.md         # Storage questions and answers
 ┣ 📂 affinity
 ┃ ┗ affinity.md        # Pod affinity/anti-affinity exercises
 ┗ README.md
```

Each `.md` file includes:

1. **Question statement** (exact task)
2. **Shell commands & outputs** (real terminal work)
3. **Explanations & notes** (why it works, exam tips)

---

🌟 Why This Matters

✅ 100% practical, with real terminal outputs
✅ Complex questions broken down step by step
✅ Open for everyone
✅ Built with honesty, sincerity, and the goal of community service

This is not just exam prep — it’s a **comprehensive Kubernetes lab**, designed to build confidence for the CKA/CKAD exams.

---

## 🚀 How to Use

### Prerequisites
- A Kubernetes cluster (e.g., Minikube, Kind, or GKE/EKS/AKS)
- `kubectl` installed and configured
- Basic to medium level Kubernetes Recources creation & troubleshooting knowledge

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/ibtisam-iq/cka-ckad-practice-labs.git
   cd cka-ckad-practice-lab
   ```
2. Pick a topic folder (e.g., `deployments/`)
3. Open the `.md` file and practice each question in your cluster
4. Compare your approach with the provided solutions and notes
5. Repeat until confident

---

## ❓ FAQ
- **Q: Can I practice without a cluster?**  
  A: A local cluster like Minikube or Kind is recommended.

---

## 🤝 Contributing
Want to add questions or improve solutions?
1. Fork the repository.
2. Create a branch (`git checkout -b new-question`).
3. Add or edit `.md` files in the relevant topic folder.
4. Submit a pull request with a clear description.

---

## 🙏 Credits
Thanks to:

* [KodeKloud](https://kodekloud.com)
* [KillerCoda](https://killercoda.com/)
* [Killer.sh](https://killer.sh)
* **ChatGPT** (for explanations and insights)

---

## 📜 License
This project is licensed under the [MIT License](LICENSE).

---

## ✨ Final Note
This lab is my way of giving back, built with **sincerity and dedication**. If it helps you, please share it with others. Together, we grow stronger 🚀

For feedback or questions, open a [GitHub issue](https://github.com/ibtisam-iq/cka-ckad-practice-labs/issues).

---
