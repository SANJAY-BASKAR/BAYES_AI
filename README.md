
# Bayesian Network Project

This project implements a Bayesian Network for probabilistic reasoning. It is based on concepts from Harvard's CS50 AI, Week 2.

## 📌 Overview
This project models a Bayesian Network with nodes representing real-world dependencies, such as:

- **Rain**: Whether it rains or not.
- **Maintenance**: Whether maintenance is scheduled.
- **Train**: Whether the train is running on time.
- **Appointment**: Whether you will make it to your appointment.

The relationships between these events are modeled using conditional probabilities.

## 📂 Project Structure

```
📦 BAYES
 ┣ 📜 inference.py    # Performs probabilistic inference on the network
 ┣ 📜 likelihood.py   # Computes likelihoods based on evidence
 ┣ 📜 model.py        # Defines the Bayesian Network and dependencies
 ┣ 📜 sample.py       # Generates samples from the Bayesian Network
```

## ⚙️ Dependencies

Ensure you have `pgmpy` installed:

```sh
pip install pgmpy
```

## 🚀 Usage

Run the model to define the network:

```sh
python model.py
```

Perform inference with:

```sh
python inference.py
```

## 🎓 References
- Harvard CS50 AI, Week 2: [Bayesian Networks](https://cs50.harvard.edu/ai/)
- `pgmpy` Documentation: [pgmpy.org](https://pgmpy.org/)

---
