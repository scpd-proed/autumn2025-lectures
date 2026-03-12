## XCS221 Executable Lectures

This repository contains all the executable lectures, made using [edtrace](https://github.com/percyliang/edtrace).

**No local setup required!** Use the links below to access the compiled, production-ready lecture notes directly in your browser.

If you notice any problems or have any questions, please file a GitHub issue or submit a pull request.

---

## Module 1: Introduction

### Foundations

- [welcome](https://scpd-proed.github.io/xcs221/?trace=welcome)
- [history](https://scpd-proed.github.io/xcs221/?trace=history)

## Module 2: Machine Learning

### Tensors and Einops

- [tensors](https://scpd-proed.github.io/xcs221/?trace=tensors)

### Foundational ML

- [backpropagation](https://scpd-proed.github.io/xcs221/?trace=backpropagation)
- [linear_regression](https://scpd-proed.github.io/xcs221/?trace=linear_regression)

### Classification

- [linear_classification](https://scpd-proed.github.io/xcs221/?trace=linear_classification)

### Language Models

- [language_models](https://scpd-proed.github.io/xcs221?trace=linear_classification&step=586)

### Deep Learning

- [deep_learning](https://scpd-proed.github.io/xcs221/?trace=deep_learning)

## Module 3: Search

### Foundational Search

- [foundational_search](https://scpd-proed.github.io/xcs221/?trace=search)

### Heuristic Search

- [heuristic_search](https://scpd-proed.github.io/xcs221/?trace=ucs_astar)

## Module 4: Reinforcement Learning

### Markov Decision Processes (MDPs)

- [mdp](https://scpd-proed.github.io/xcs221/?trace=mdp)

### Foundational RL

- [foundational_rl](https://scpd-proed.github.io/xcs221/?trace=reinforcement_learning)

### Policy Gradients

- [policy_gradients](https://scpd-proed.github.io/xcs221/?trace=policy_gradient)

## Module 5: Games

### Game Trees & Adversarial Search

- [games](https://scpd-proed.github.io/xcs221/?trace=games)

### Temporal Difference (TD) Learning

- [td_learning](https://scpd-proed.github.io/xcs221/?trace=td_learning)

### Game Theory

- [game_theory](https://scpd-proed.github.io/xcs221/?trace=simultaneous_games)


## Module 6: Bayesian Networks & Probabilistic Inference

### Bayesian Networks

- [bayesian_networks](https://scpd-proed.github.io/xcs221/?trace=bayes)

### Probabilistic Inference

- [probabilistic_inference](https://scpd-proed.github.io/xcs221/?trace=gibbs_sampling)

### Parameter Learning

- [parameter_learning](https://scpd-proed.github.io/xcs221/?trace=bayes_learning)

## Module 7: Logic

### Propositional Logic

- [propositional_logic](https://scpd-proed.github.io/xcs221/?trace=propositional_logic)

### First-order Logic

- [first_order_logic](https://scpd-proed.github.io/xcs221/?trace=first_order_logic)

## Module 8: Language Models

### Introduction to Language Models

- [language_models](https://drive.google.com/file/d/1wlEK8sS45nRL4Edo2--on_exCu3S_Jrw/view?usp=drive_link)

## Module 9: AI, Ethics, and Society

### Ethics

- [ethics](https://scpd-proed.github.io/xcs221/?trace=society)

### Economics of AI

- [economics](https://drive.google.com/file/d/1_S-_8KeVxt4hy6d4Rs3lgMI3IXmxvjCl/view?usp=drive_link)

---

## For Course Developers Only

> ⚠️ The instructions below are intended for the **course development team** and are not needed by students or contributors. They are used to update the GitHub-hosted lecture URLs.

### Prerequisites

**macOS:**
```bash
brew install graphviz
uv sync
```

**Linux:**
```bash
sudo apt-get install graphviz
uv sync
```

### Running an Executable Lecture

```bash
python -m edtrace.execute -m welcome
```

This will generate a `.json` file that wires into the static frontend and is served via GitHub Pages.
