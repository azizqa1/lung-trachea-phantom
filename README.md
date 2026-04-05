# lung-trachea-phantom
Multi-material lung and trachea physical phantom — DICOM segmentation, GOM Inspect post-processing, and FDM fabrication

Patient-specific lung and trachea phantom fabricated using DICOM segmentation,
mesh post-processing, and multi-material FDM 3D printing.

# Status
Completed — Academic project, Poznan University of Technology (2025–2026)

# Objective
Produce a physical anatomical phantom replicating differential tissue stiffness
of lung parenchyma and trachea — for surgical planning and simulation applications.

## Workflow

1. Segmentation
- Segmented lung and trachea anatomy slice-by-slice from DICOM CT dataset in InVesalius
- Exported patient-specific STL meshes

2. Mesh Post-Processing
- Imported STL into GOM Inspect
- Removed segmentation artifacts and incorrectly placed tissue regions
- Corrected surface topology and smoothed mesh for manufacturing readiness

3. Mold Design
- Designed negative die mold in 3D Builder around lung geometry
- Mold used to cast soft material fill in correct anatomical shape

4. Multi-Material Fabrication
- Lung parenchyma: soft TPU — replicates compliant tissue behavior
- Trachea: rigid PLA — replicates cartilaginous structure

Tools Used

InVesalius-DICOM segmentation, STL export
GOM Inspect-Mesh post-processing, artifact removal
3D Builder-Mold/die design
UltiMaker Cura -Slicing
FDM 3D Printer-Multi-material fabrication

 Files
- `/Lungs_Screenshots` — Process screenshots from InVesalius and GOM Inspect
- `/Invesalius` — Segmentation project files
- `/GoM_Inspect_Lungs_Trachea` — Mesh inspection files
- `/3D_Builder` — Mold and die geometry files
