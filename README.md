# Hello I'm Étienne!
Montreal-based former Lookdev Technical Director at Framestore — 8 years in film and episodic VFX production — switching into ML engineering and software development.

After working inside large production pipelines for years, I realized I was more drawn to understanding the underlying logic and structure of systems than the outputs they produced. ML felt like the natural space to develop that further.

iNaturalist observations turned out to be a surprisingly rich problem to learn on: messy real-world data, genuine domain constraints, and a meaningful use case — the kind of problem I'm looking for, whatever the field.

Starting a B.Sc. in Computer Science & Mathematics at Université de Montréal in Fall 2026.

---

## What I'm working on

### [inat-obs-scorer](https://github.com/etiennegodin/inat-obs-scorer)
**Expert review prioritization engine for iNaturalist**

Goal: reduce expert review time wasted on low-impact observations and accelerate biodiversity data validation.

A production-style binary classifier that scores "Needs ID" plant observations in Québec on their probability of reaching Research Grade — helping triage expert identifier time toward the observations most likely to benefit from it.

- ROC-AUC 0.88 · 98.2% precision @ top-500 (review budget framing)
- Explicit handling of temporal leakage across labels, features, and validation
- Point-in-time label reconstruction via reimplementation of the iNaturalist community taxon algorithm (DuckDB macro)
- Taxon difficulty modeling (Bayesian shrinkage) · species confusion graph (DuckPGQ)
- End-to-end pipeline: LightGBM + Optuna + MLflow + async API enrichment

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
