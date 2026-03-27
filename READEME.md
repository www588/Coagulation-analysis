\# Reinforcement Learning for Coagulation Dysfunction Decision Support

A deep reinforcement learning (DRL) framework for clinical decision support in bleeding and thrombosis management.



\## Project Overview

This project implements a DRL-based system to optimize anticoagulant/antiplatelet/hemostatic interventions for patients with coagulation disorders.



\### Notebooks

\- `01\_data\_preprocessing.ipynb`: Data cleaning, time feature engineering, and intervention classification

\- `02\_state\_scoring.ipynb`: Dynamic state construction (bleeding tendency Yx, coagulation tendency Yy)

\- `03\_rl\_model.ipynb`: BiLSTM+attention RL model training with early stopping

\- `04\_statistical\_analysis.ipynb`: Stratified analysis, visualization, and feature importance



\## Installation

```bash

git clone https://github.com/www588/Coagulation-analysis.git

cd coagulation-rl-decision-system

pip install -r requirements.txt

