# Hello I'm Étienne!
Montreal-based former Lookdev Technical Director at Framestore — 8 years in film and episodic VFX production — switching into ML engineering and software development.

After working inside large production pipelines for years, I realized I was more drawn to understanding the underlying logic and structure of systems than the outputs they produced. ML felt like the natural space to develop that further.

iNaturalist observations turned out to be a surprisingly rich problem to learn on: messy real-world data, genuine domain constraints, and a meaningful use case — the kind of problem I'm looking for, whatever the field.

Starting a B.Sc. in Computer Science & Mathematics at Université de Montréal in Fall 2026.

---

## What I'm working on

### [inat-obs-scorer](https://github.com/etiennegodin/inat-obs-scorer)
Probabilistic ranking engine for iNaturalist expert review queues.

A production-style ML pipeline designed to solve the "discovery gap" for Québec plant observations—routing expert identifier attention toward observations cases that fail to self-resolve within 7 days.

Performance: 3.29× lift at 94% precision (top 5% of test set; $n=1,374$) on held-out 2024 data.

Operational Flexibility: Designed for varying reviewer bandwidth with configurable operating points: High-Recall (90%) for broad discovery and Balanced (75%) for high-confidence queue management.

Engineering Rigor: Implements a strict temporal split strategy with gap buffers to mitigate four distinct leakage vectors (Label, Feature, Split, and CV).

Domain Logic: Re-derives Research Grade labels via a DuckDB table macro implementing the iNaturalist community taxon algorithm.

Feature Engineering: Leverages Bayesian-shrunk observer/taxon history and species confusion graph topology (55k edges) via DuckPGQ.

Stack: Python (3.12), DuckDB, LightGBM, Optuna, MLflow, DVC.

---

### [NukeKit](https://github.com/etiennegodin/NukeKit)
**Gizmo version control for Nuke compositors**

Built as an exercise in software architecture — four-layer design, ManifestStore persistence, typed exception hierarchy, atomic writes. A small project but a useful one for learning how to structure Python systems properly.

---

## Stack

```
Python · SQL · DuckDB · LightGBM · scikit-learn · Optuna · MLflow · SHAP · DVC · Git · Linux
```

## Background

Previously: Lookdev Technical Director at Framestore (8 years)  
Worked on look development for CG assets across major film and episodic productions including *How to Train Your Dragon*, *Fallout SE1*, *Captain Marvel* and others    

---

## Looking for

ML Engineering / Data Engineering / Backend Internships (Montreal · Available Summer 2026)     
Seeking roles where I can apply 8 years of production pipeline experience to scalable machine learning systems and data-intensive backends.

etiennegodin@duck.com · [linkedin.com/in/etiennegodin](https://linkedin.com/in/etiennegodin)
