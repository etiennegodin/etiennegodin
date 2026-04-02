# Hello I'm Étienne!
Montreal-based former Lookdev Technical Director at Framestore — 8 years in film and episodic VFX production — switching into ML engineering and software development.

After working inside large production pipelines for years, I realized I was more drawn to understanding the underlying logic and structure of systems than the outputs they produced. ML felt like the natural space to develop that further.

iNaturalist observations turned out to be a surprisingly rich problem to learn on: messy real-world data, genuine domain constraints, and a meaningful use case — the kind of problem I'm looking for, whatever the field.

Starting a B.Sc. in Computer Science & Mathematics at Université de Montréal in Fall 2026.

---

## What I'm working on

### [inat-obs-scorer](https://github.com/etiennegodin/inat-obs-scorer)
**Expert review prioritization engine for iNaturalist**

A production-style ML pipeline that scores Québec plant observations on their probability of reaching Research Grade — routing expert identifier attention toward observations that need it most.

Top 5% of scored observations yield **3.29× lift at 94% precision** on held-out 2024 data.

- Point-in-time feature engineering with temporal train/val/test splits and gap buffers — no leakage across labels, features, or validation
- Label reconstruction via reimplementation of the iNaturalist community taxon algorithm (DuckDB macro)
- Bayesian shrinkage at taxon, observer, and observer×taxon levels · species confusion graph with 22k edges (DuckPGQ)
- End-to-end pipeline: LightGBM · Optuna · MLflow · DVC

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
