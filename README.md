# PIGMM-for-AM
Gaussian Mixture Models for Additive Manufacturing

This repository provides an example of using a Gaussian Mixture Models to detect defects in Additive Manufacturing processes, specifically in the case of the Laser Powder Bed Fusion (L-PBF) technology. 
More details can be found in the paper associated with this repository.


## Dataset structure description

We do not provide the dataset here, but it is easy to replace it with your own dataset. The dataset used in the paper contains experimental data related to L-PBF, where each row represents a unique experimental condition with the following columns:
1) Alloy: Type or identifier of the alloy used (e.g., SS316-1).
2) Powder size: Size of the powder particles in micrometers (e.g., 36.6).
3) Laser power: Power of the laser used, likely in Watts (e.g., 25, 50).
4) Scan speed: Speed at which the laser scans the powder bed, likely in mm/s (e.g., 80, 110, 140).
5) Beam diameter: Diameter of the laser beam, possibly in millimeters (e.g., 0.08).
6) Layer thickness: Thickness of each deposited layer, possibly in millimeters (e.g., 0.1).
7) Thermal diffusivity: Material property indicating heat conduction efficiency (e.g., 0.00002).
8) Balling defect: Binary indicator for the presence of balling defects (1 = defect present). This is the target variable for defect detection.


## Installation

To install the required Python packages, run:

```bash
pip install -r requirements.txt

## License

This code is licensed under the MIT License.

## Citation

If you use this code in your research, please cite the following paper:

Sebastian Basterrech, Shuo Shan, Debabrata Adhikari, and Sankhya Mohanty, "Physics-Informed Mixture Models and Surrogate Models for Precision Additive Manufacturing, " Artificial Intelligence for Science, Copenhagen, 2025. URL: https://arxiv.org/pdf/2510.26586

