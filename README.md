# Geometric Error Modeling and Compensation for Rotating Scan Remote Sensing Satellites

This repository is the project page for a manuscript on geometric positioning and compensation for a rotating-scan remote sensing satellite. It currently presents a concise overview of the study and selected author-generated visual results.

> **Project status:** Manuscript in preparation for submission.

## Overview

Rotating-scan imaging expands cross-track coverage by rotating the payload during acquisition, but the additional mechanism introduces scan-angle-dependent geometric errors and strongly varying ground sampling distance (GSD). The study develops a unified framework that:

- explicitly models scan-angle and rotation-axis tilt errors within the rigorous imaging chain;
- estimates compensation parameters from ground control points (GCPs) distributed over multiple scan angles;
- accounts for angle-dependent observation uncertainty through GSD-aware weighted least squares;
- evaluates point-wise geolocation accuracy, parameter observability, model limitations, and local relative geometric distortion.

## Method overview

The experimental workflow follows four stages:

1. introduce representative rotating-mechanism errors into the auxiliary geometry;
2. estimate error parameters from GCP constraints;
3. feed the estimated parameters back into positioning and geometric-correction models;
4. evaluate independent check points and image-level geometric consistency.

Two compensation models are considered. The first models low-order scan-angle error, while the second additionally represents rotation-axis tilt. Equal-weight and GSD-aware weighted estimation are compared under spatially varying observation uncertainty.

## Selected visual results

### Rotating-mechanism error compensation

![Rotating-mechanism error compensation](assets/mechanism_compensation.png)

The comparison illustrates the scan-angle-dependent error amplification and the contribution of explicit rotation-axis modeling.

### GSD-aware weighted estimation

![GSD-aware weighted estimation](assets/gsd_aware_weighting.png)

The figure connects anisotropic GSD growth with observation weighting and positioning-error propagation.

### GCP angular coverage and observability

![GCP angular coverage and observability](assets/gcp_coverage_observability.png)

The results show how scan-angle coverage affects parameter conditioning and the stability of the geometric compensation model.

### Image-level closed-loop validation

![Image-level closed-loop validation](assets/closed_loop_validation.png)

Independent check-point evaluation provides an image-level closed-loop assessment of the estimated compensation parameters.

### Local relative geometric distortion

![Local relative geometric distortion](assets/relative_geometric_distortion.png)

The analysis separates overall geolocation displacement from translation-removed local distortion and directional distance-preservation errors.

Additional information about the displayed figures is available in [the figure index](docs/figure_index.md).

## Code and data availability

This repository serves as a project page for a manuscript currently being prepared for submission. At this stage, it provides only a high-level description of the work and selected author-generated visualizations.

Source code, detailed experimental configurations, auxiliary data, and full-resolution simulation imagery are not included during manuscript preparation and peer review. Subject to journal policy and institutional, coauthor, intellectual-property, third-party-data, and legal approvals, the authors intend to release the reproducibility materials after acceptance or publication. The final release scope and license will be stated here.

Citation information will be added upon publication.

## Rights and reuse

The current project-page materials are provided for scholarly communication only. See [NOTICE.md](NOTICE.md) for the applicable terms. Separate licenses may be provided for source code and data in a later reproducibility release.
