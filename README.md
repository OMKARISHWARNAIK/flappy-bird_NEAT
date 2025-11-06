# Flappy Bird AI with NEAT

A Python project where an **AI learns to play the Flappy Bird game autonomously** using **NeuroEvolution of Augmenting Topologies (NEAT)** — a sophisticated evolutionary algorithm. This project combines **game development, AI, and machine learning** to create a visually engaging, interactive demonstration of AI learning in real-time.

---

## 🔹 Project Overview

The goal of this project is to demonstrate how **AI can learn and adapt** to play a game without human intervention. The AI is trained using the NEAT algorithm, which evolves a population of "birds" generation by generation:

- Each generation has multiple birds that try to navigate through pipes.
- The best-performing birds’ parameters are combined and mutated to create the next generation.
- Over time, the AI improves, learning strategies to survive longer in the game.

This project showcases **practical AI implementation**, **evolutionary algorithms**, and **game mechanics** integration.

---

## 🔹 Features

- Fully playable Flappy Bird game implemented in **Python** using **pygame**.
- AI-controlled birds that evolve over generations using **neat-python**.
- Real-time visualization of AI progress.
- Adjustable NEAT parameters (population size, mutation rate, etc.).
- Demonstrates object-oriented programming, algorithmic thinking, and AI integration.

---

## 🔹 Tech Stack & Technologies Used

| Technology | Purpose |
|------------|---------|
| **Python 3.11** | Core programming language |
| **pygame** | Game development (graphics, user input, animation) |
| **neat-python** | Implements NEAT (NeuroEvolution of Augmenting Topologies) |
| **Object-Oriented Programming (OOP)** | To structure game entities like Bird, Pipe, and Base |
| **Evolutionary Algorithms** | For AI learning via selection, mutation, and crossover |
| **VS Code / PyCharm** | Development environment for coding and testing |
| **Git & GitHub** | Version control and code hosting |

---

## 🔹 How the AI Works

1. **Initialization:**  
   - A population of birds is created, each with a unique neural network.

2. **Evaluation:**  
   - Birds attempt to navigate through the pipes.  
   - Each bird’s fitness score is based on distance traveled and survival time.

3. **Selection & Reproduction:**  
   - Top-performing birds are selected.  
   - Their neural networks are combined (crossover) and slightly mutated.

4. **Next Generation:**  
   - The new generation of birds inherits traits from the previous best performers.  
   - Process repeats until the AI learns to play efficiently.

---

## 🔹 Installation & Running the Project

1. **Clone the repository:**

```bash
git clone https://github.com/_flappy_bird.git
cd _flappy_bird
🔹 Learning Outcomes

This project demonstrates my  ability to:

Integrate AI/ML concepts with real-world applications.
Implement evolutionary algorithms using NEAT.
Develop a game engine using Python’s pygame.
Apply object-oriented programming principles in structuring complex systems.
Use version control and GitHub for project management
screenshots
<img width="1918" height="1078" alt="vs game" src="https://github.com/user-attachments/assets/218f8fc0-8d30-446e-b8a2-a2beeb19c9dc" />
live demo link "https://docs.google.com/videos/d/1P1KZU7T_wLtF3m46BesbolpT6yu8sa3ljrqqJJ94kcY/edit?usp=sharing"

