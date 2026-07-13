# Figure index

The project page combines conceptual diagrams, representative simulated imagery, and selected quantitative figures. No source code, auxiliary-data records, geographic coordinates, or full-resolution source imagery are distributed.

## Main-page visualizations

| File | Content | Role in the study |
| --- | --- | --- |
| `rotating_scan_error_overview.png` | Rotating payload, scanning geometry, scan-angle error, and rotation-axis tilt | Introduces the imaging concept and mechanism-specific error sources |
| `rigorous_geometric_model.png` | Object--image mapping within the rigorous geometric chain | Defines the physical basis of positioning and correction |
| `rotating_scan_error_principle.png` | Nominal and perturbed imaging rays, ground intersections, and scan-direction geometry | Illustrates how mechanism errors propagate into geolocation error |
| `scan_angle_imaging_examples.png` | Simulated Baotou target-field observations at representative scan angles | Visualizes scan-angle-dependent deformation and GSD variation |
| `mechanism_compensation.png` | Error-level sensitivity and scan-angle-dependent residuals | Summarizes the principal compensation result |

## Supplementary project-page visualizations

| File | Content | Role in the study |
| --- | --- | --- |
| `dynamic_error_residuals.png` | Residual response to unmodeled dynamic disturbances | Characterizes the applicability boundary of the low-order model |
| `gsd_aware_weighting.png` | Along-/cross-track GSD variation and weighted-estimation statistics | Connects GSD anisotropy with weighted estimation |
| `gcp_coverage_observability.png` | GCP scan-angle coverage, accuracy, and conditioning | Evaluates parameter observability under angular constraints |
| `closed_loop_validation.png` | Image measurement errors and independent check-point results | Quantifies image-level closed-loop accuracy |
| `relative_geometric_distortion.png` | Absolute displacement, translation-removed residuals, and pair-distance errors | Evaluates local relative geometric consistency |

The Baotou and closed-loop image panels contain simulation products constructed from basemap resources. Their inclusion in a public repository remains subject to confirmation of the applicable provider attribution and redistribution terms.
