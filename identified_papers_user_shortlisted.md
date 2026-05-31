# Identified papers — user-curated stack (Stack 3 cap-stone)

Each entry is a paper from a user-curated folder or tree, enriched with OpenAlex metadata. Stack 3 trusts the source (every PDF was placed by the user). Verify and validate gates are skipped — see new_ideas.md for the architecture.

---

1) Raghavan 1994 — Forward and inverse problems in elasticity imaging of soft tissues — IEEE Transactions on Nuclear Science — DOI:10.1109/23.322961

   **Metadata (OpenAlex):**
   - **Title:** Forward and inverse problems in elasticity imaging of soft tissues
   - **DOI:** 10.1109/23.322961
   - **OpenAlex ID:** https://openalex.org/W2107552043
   - **Year:** 1994
   - **Venue:** IEEE Transactions on Nuclear Science
   - **Type:** article  |  **Language:** en  |  **Refs:** 17  |  **Cited by:** 99  |  **OA status:** closed
   - **Authors:**
     - Kamaldev Raghavan (University of Michigan–Ann Arbor)
     - A.E. Yagle (University of Michigan–Ann Arbor)
   - **Topics:** Ultrasound Imaging and Elastography, Photoacoustic and Ultrasonic Imaging, Ultrasonics and Acoustic Wave Propagation
   - **Concepts:** Inverse problem, Elasticity (physics), Inverse, Boundary value problem, Applied mathematics
   - **Abstract:** In elasticity imaging, a surface deformation is applied to an object using small pistons, and the resulting induced strains in the interior of the object are measured using ultrasonic imaging. Two important problems are considered: (1) the forward problem of determining the strains induced by a known deformation of an object with known elasticity; and (2) the inverse problem of reconstructing elasticity from measured strains and the equations of equilibrium. The method of finite differences is used to solve the forward problem for a given piston configuration; some nontrivial issues arise in determining boundary conditions. The finite difference equations are then rearranged into a linear system of equations which formulates the inverse problem; this system can be solved for the unknown elasticities. This formulation of the inverse problem is completely consistent with the forward problem; this is useful for iterative methods in which the deformation is adaptively changed. A comparison between simulated and actual measured results demonstrate the feasibility of the proposed procedure.< <ETX xmlns:mml="http://www.w3.org/1998/Math/MathML" xmlns:xlink="http://www.w3.org/1999/xlink">&gt;</ETX>
   - **Resolution mode:** search
   - **Source paths:**
     - /home/vivekkarmarkar/Python Files/paper-stack-three-test-two/shortlisted/Mathematical Foundations/pat_scan_relevant_mathematical_foundations_linear_3D_paper_1994.pdf

---
2) Liu 2005 — Tomography-based 3-D anisotropic elastography using boundary measurements — IEEE Transactions on Medical Imaging — DOI:10.1109/tmi.2005.857232

   **Metadata (OpenAlex):**
   - **Title:** Tomography-based 3-D anisotropic elastography using boundary measurements
   - **DOI:** 10.1109/tmi.2005.857232
   - **OpenAlex ID:** https://openalex.org/W2107785764
   - **Year:** 2005
   - **Venue:** IEEE Transactions on Medical Imaging
   - **Type:** article  |  **Language:** en  |  **Refs:** 50  |  **Cited by:** 41  |  **OA status:** closed
   - **Authors:**
     - Yi Liu (University of Iowa; University of Iowa Hospitals and Clinics)
     - Lizhi Sun (University of Iowa Hospitals and Clinics)
     - Ge Wang (University of Iowa)
   - **Topics:** Ultrasound Imaging and Elastography, Elasticity and Material Modeling, Ultrasonics and Acoustic Wave Propagation
   - **Concepts:** Imaging phantom, Isotropy, Anisotropy, Tomography
   - **Abstract:** While ultrasound- and magnetic resonance-based elastography techniques have proved to be powerful biomedical imaging tools, most approaches assume isotropic material properties. In this paper, a general framework is developed for tomography-based anisotropic elastography. An anatomically well- motivated piece-wise homogeneous model is proposed to represent a class of biological objects consisting of different regions. With established tomography modality, static displacements are measured on the entire external and internal boundaries, and the force distribution is recorded on part of the external surface. A principle is proposed to identify the anisotropic elastic moduli of the constituent regions with the obtained boundary measurements. The reconstruction procedure is optimization-based with minimizing an objective function that measures the difference between the predicted and observed displacements. Analytic gradients of the objective function with respect to the elastic moduli are calculated using an adjoint method, and are utilized to significantly improve the numerical efficiency. Simulations are performed to identify the elastic moduli in a breast phantom consisting of soft tissue and a hard tumor. For isotropic phantom, one set of the boundary measurements enables unique reconstruction results for the tissue and tumor. For anisotropic phantom, however, multiple sets of the measurements corresponding to different deformation modes become necessary.
   - **Resolution mode:** search
   - **Source paths:**
     - /home/vivekkarmarkar/Python Files/paper-stack-three-test-two/shortlisted/Statics/IOWA_surface_displacement_paper_2005.pdf

---
3) Mei 2017 — Mechanics Based Tomography: A Preliminary Feasibility Study — Sensors — DOI:10.3390/s17051075

   **Metadata (OpenAlex):**
   - **Title:** Mechanics Based Tomography: A Preliminary Feasibility Study
   - **DOI:** 10.3390/s17051075
   - **OpenAlex ID:** https://openalex.org/W2612717027
   - **Year:** 2017
   - **Venue:** Sensors
   - **Type:** article  |  **Language:** en  |  **Refs:** 31  |  **Cited by:** 19  |  **OA status:** gold
   - **Authors:**
     - Yue Mei (Texas A&M University)
     - Sicheng Wang (Texas A&M University)
     - Xin Shen (Texas A&M University)
     - Stephen Rabke (Texas A&M University)
     - Sevan Goenezen (Texas A&M University)
   - **Topics:** Electrical and Bioimpedance Tomography, Ultrasound Imaging and Elastography, Photoacoustic and Ultrasonic Imaging
   - **Concepts:** Shear modulus, Stiffness, Shear (geology), Digital image correlation, Modulus, Boundary value problem
   - **Abstract:** We present a non-destructive approach to sense inclusion objects embedded in a solid medium remotely from force sensors applied to the medium and boundary displacements that could be measured via a digital image correlation system using a set of cameras. We provide a rationale and strategy to uniquely identify the heterogeneous sample composition based on stiffness (here, shear modulus) maps. The feasibility of this inversion scheme is tested with simulated experiments that could have clinical relevance in diagnostic imaging (e.g., tumor detection) or could be applied to engineering materials. No assumptions are made on the shape or stiffness quantity of the inclusions. We observe that the novel inversion method using solely boundary displacements and force measurements performs well in recovering the heterogeneous material/tissue composition that consists of one and two stiff inclusions embedded in a softer background material. Furthermore, the target shear modulus value for the stiffer inclusion region is underestimated and the inclusion size is overestimated when incomplete boundary displacements on some part of the boundary are utilized. For displacements measured on the entire boundary, the shear modulus reconstruction improves significantly. Additionally, we observe that with increasing number of displacement data sets utilized in solving the inverse problem, the quality of the mapped shear moduli improves. We also analyze the sensitivity of the shear modulus maps on the noise level varied between 0.1% and 5% white Gaussian noise in the boundary displacements, force and corresponding displacement indentation. Finally, a sensitivity analysis of the recovered shear moduli to the depth, stiffness and the shape of the stiff inclusion is performed. We conclude that this approach has potential as a novel imaging modality and refer to it as Mechanics Based Tomography (MBT).
   - **Resolution mode:** search
   - **Source paths:**
     - /home/vivekkarmarkar/Python Files/paper-stack-three-test-two/shortlisted/Statics/Mechanics_based_Tomography_paper_2017.pdf

---
4) Zhang 2022 — Analyses of internal structures and defects in materials using physics-informed neural networks — Science Advances — DOI:10.1126/sciadv.abk0644

   **Metadata (OpenAlex):**
   - **Title:** Analyses of internal structures and defects in materials using physics-informed neural networks
   - **DOI:** 10.1126/sciadv.abk0644
   - **OpenAlex ID:** https://openalex.org/W4213199992
   - **Year:** 2022
   - **Venue:** Science Advances
   - **Type:** article  |  **Language:** en  |  **Refs:** 60  |  **Cited by:** 344  |  **OA status:** gold
   - **Authors:**
     - Enrui Zhang (Brown University)
     - Ming Dao (Massachusetts Institute of Technology)
     - George Em Karniadakis (Brown University)
     - Subra Suresh (Nanyang Technological University)
   - **Topics:** Model Reduction and Neural Networks, Machine Learning in Materials Science, Non-Destructive Testing Techniques
   - **Concepts:** Nonlinear system, Artificial neural network, Void (composites), Differentiable function
   - **Abstract:** Characterizing internal structures and defects in materials is a challenging task, often requiring solutions to inverse problems with unknown topology, geometry, material properties, and nonlinear deformation. Here, we present a general framework based on physics-informed neural networks for identifying unknown geometric and material parameters. By using a mesh-free method, we parameterize the geometry of the material using a differentiable and trainable method that can identify multiple structural features. We validate this approach for materials with internal voids/inclusions using constitutive models that encompass the spectrum of linear elasticity, hyperelasticity, and plasticity. We predict the size, shape, and location of the internal void/inclusion as well as the elastic modulus of the inclusion. Our general framework can be applied to other inverse problems in different applications that involve unknown material properties and highly deformable geometries, targeting material characterization, quality assurance, and structural design.
   - **Resolution mode:** search
   - **Source paths:**
     - /home/vivekkarmarkar/Python Files/paper-stack-three-test-two/shortlisted/Statics/PINNs_Karniadakis_elasticity_paper_2022.pdf

---
5) Konofagou 2004 — Palpation tomography - a new technique for modulus estimation in Elastography — ? — DOI:10.1109/ultsym.2003.1293486

   **Metadata (OpenAlex):**
   - **Title:** Palpation tomography - a new technique for modulus estimation in Elastography
   - **DOI:** 10.1109/ultsym.2003.1293486
   - **OpenAlex ID:** https://openalex.org/W2548465179
   - **Year:** 2004
   - **Venue:** ?
   - **Type:** article  |  **Language:** en  |  **Refs:** 8  |  **Cited by:** 1  |  **OA status:** closed
   - **Authors:**
     - Elisa E. Konofagou (Columbia University)
     - T.P. Harrigan (Exponent (United States))
   - **Topics:** Ultrasound Imaging and Elastography, Elasticity and Material Modeling, Photoacoustic and Ultrasonic Imaging
   - **Concepts:** Modulus, Materials science, Displacement (psychology), Finite element method
   - **Abstract:** In Elastography, strain estimation has been shown to be far more reliable compared to the elastic properties obtained using reconstruction techniques. In this study, to make the method less sensitive to noise in the experimental data and inspired by the clinical practice of palpation (i.e., the use of sequential finger loading), we investigated the effect of using several different smaller quasi-static load cases (instead of a one-time load on the whole boundary), with the error indicator taken as the sum of the errors from each load case. This increased the ratio of measurements to the fitted parameters, which made the method less sensitive to random errors. To demonstrate this effect, we calculated displacements from a two-dimensional, quadrilateral, plane-strain, finite-element model of a 40-by-40 mm region containing a cylindrical inclusion (7 mm in diameter) three-times stiffer than the background. The ratio of nodal pressures was chosen to produce approximately 0.75% strain. Known amounts of random displacement errors were then added at a signal-to-noise ratio varying from 60 dB to 20 dB. Elastic modulus reconstructions using the noisy displacement results from a single, total-boundary, pressure load (as is typically applied in elastography) were compared to reconstructions using data from nine smaller-width loading cases, and the reconstructed modulus distributions were compared to the original model parameters. It was found that in the cases of 60 dB and 40 dB the multiple loading cases resulted in noise reduction in the modulus reconstruction by at least a twofold compared to the single-loading case, at the expense of a 'shadowing' effect (i.e., erroneous modulus estimates) underneath the inclusion that could be eliminated by using larger loading areas for the individual loading cases. Finally, at 20 dB both the large single-load and combined, smaller five-load cases failed to accurately reconstruct the modulus of the inclusion; depicting thus a fundamental limit on the reconstruction method.
   - **Resolution mode:** search
   - **Source paths:**
     - /home/vivekkarmarkar/Python Files/paper-stack-three-test-two/shortlisted/Statics/Palpation_Tomography_paper_2003.pdf

---
6) Olson 2012 — An inverse problem approach to stiffness mapping for early detection of breast cancer — Inverse Problems in Science and Engineering — DOI:10.1080/17415977.2012.700710

   **Metadata (OpenAlex):**
   - **Title:** An inverse problem approach to stiffness mapping for early detection of breast cancer
   - **DOI:** 10.1080/17415977.2012.700710
   - **OpenAlex ID:** https://openalex.org/W2060183497
   - **Year:** 2012
   - **Venue:** Inverse Problems in Science and Engineering
   - **Type:** article  |  **Language:** en  |  **Refs:** 76  |  **Cited by:** 13  |  **OA status:** closed
   - **Authors:**
     - L.G. Olson (Rose–Hulman Institute of Technology)
     - R.D. Throne (Rose–Hulman Institute of Technology)
   - **Topics:** Ultrasound Imaging and Elastography, Photoacoustic and Ultrasonic Imaging, Ultrasonics and Acoustic Wave Propagation
   - **Concepts:** Inverse problem, Finite element method, Stiffness, Deflection (physics), Computer science
   - **Abstract:** Early detection of breast cancer will continue to be crucial in improving patient survival rates. Our ultimate goal is to develop a system that automates, quantifies and enhances the resolution of the manual breast exam. In this study, we examine computational techniques which use breast surface force and deflection measurements to create detailed maps of the elastic modulus of the interior of the breast tissue. This approach is a reformulation of our earlier two-dimensional technique to make it more practical and we extend the approach to three dimensions. Finite element methods were used to model the tissue response (reaction force and surface displacements) to applied surface indentations. A variety of test cases with assumed tumour locations were defined, and ‘measured results’ were created. Numerical noise was added to these simulated measurements at two noise levels. A genetic algorithm was developed to identify the distribution of tissue material properties within the breast given the ‘measured’ reaction forces and surface displacements. For our two- and three-dimensional model problems, tumours as small as 1 cm could be detected reliably at a signal-to-noise ratio of 23 dB.
   - **Resolution mode:** search
   - **Source paths:**
     - /home/vivekkarmarkar/Python Files/paper-stack-three-test-two/shortlisted/Statics/Rose_Hulman_pat_scan_idea_paper_2013.pdf

---
7) Peters 2007 — Digital Image Elasto-Tomography: Mechanical Property Reconstruction from Surface Measured Displacement Data — University of Canterbury Research Repository (University of Canterbury) — DOI:10.26021/2670

   **Metadata (OpenAlex):**
   - **Title:** Digital Image Elasto-Tomography: Mechanical Property Reconstruction from Surface Measured Displacement Data
   - **DOI:** 10.26021/2670
   - **OpenAlex ID:** https://openalex.org/W2120686888
   - **Year:** 2007
   - **Venue:** University of Canterbury Research Repository (University of Canterbury)
   - **Type:** article  |  **Language:** en  |  **Refs:** 83  |  **Cited by:** 3  |  **OA status:** green
   - **Authors:**
     - Ashton Peters
   - **Topics:** Advanced X-ray and CT Imaging, Photoacoustic and Ultrasonic Imaging, Medical Imaging Techniques and Applications
   - **Concepts:** Property (philosophy), Tomography, Displacement (psychology), Computer vision, Geology, Surface (topology)
   - **Abstract:** Interest in elastographic techniques for soft tissue imaging has grown as relevant research continues to indicate a correlation between tissue histology and mechanical stiffness. Digital Image Elasto-Tomography (DIET) presents a novel method for identifying cancerous lesions via a three-dimensional image of elastic properties. Stiffness reconstruction with DIET takes steady-state motion captured with a digital camera array as the input to an elastic property reconstruction algorithm, where finite element methods allow simulation of phantom motion at a range of internal stiffness distributions. The low cost and high image contrast achievable with a DIET system may be particularly suited to breast cancer screening, where traditional modalities such as mammography have issues with limited sensitivity and patient discomfort. Proof of concept studies performed on simulated data sets confirmed the potential of the DIET technique, leading to the development of an experimental apparatus for surface motion capture from a range of soft tissue approximating phantoms. Error studies performed on experimental data from these phantoms using a limited number of shape and modulus parameters indicated that accurate measurements of surface motion provide sufficient information to identify a stiffness distribution in both homogeneous and heterogeneous cases. The elastic reconstruction performed on simulated and experimental data considered both deterministic and stochastic algorithms, with a combination of the two approaches found to give the most accurate results, for a realistic increase in computational cost. The reconstruction algorithm developed has the ability to successfully resolve a hard spherical inclusion within a soft phantom, and in addition demonstrated promise in reconstructing the correct stiffness distribution when no inclusion is present.
   - **Resolution mode:** search
   - **Source paths:**
     - /home/vivekkarmarkar/Python Files/paper-stack-three-test-two/shortlisted/Vibrations/DIET_vibrations_PhD_thesis_2007.pdf

---
8) Feng 2022 — Visual Vibration Tomography: Estimating Interior Material Properties from Monocular Video — 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) — DOI:10.1109/cvpr52688.2022.01575

   **Metadata (OpenAlex):**
   - **Title:** Visual Vibration Tomography: Estimating Interior Material Properties from Monocular Video
   - **DOI:** 10.1109/cvpr52688.2022.01575
   - **OpenAlex ID:** https://openalex.org/W3150331915
   - **Year:** 2022
   - **Venue:** 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
   - **Type:** article  |  **Language:** en  |  **Refs:** 71  |  **Cited by:** 12  |  **OA status:** green
   - **Authors:**
     - Berthy T. Feng (California Institute of Technology)
     - Alexander C. Ogren (California Institute of Technology)
     - Chiara Daraio (California Institute of Technology)
     - Katherine L. Bouman (California Institute of Technology)
   - **Topics:** 3D Surveying and Cultural Heritage, Optical measurement and interference techniques, Advanced Vision and Imaging
   - **Concepts:** Tomography, Monocular, Computer vision, Computer science, Vibration, Artificial intelligence
   - **Abstract:** An object's interior material properties, while invisible to the human eye, determine motion observed on its surface. We propose an approach that estimates heterogeneous material properties of an object from a monocular video of its surface vibrations. Specifically, we show how to estimate Young's modulus and density throughout a 3D object with known geometry. Knowledge of how these values change across the object is useful for simulating its motion and characterizing any defects. Traditional nondestructive testing approaches, which often require expensive instruments, generally estimate only homogenized material properties or simply identify the presence of defects. In contrast, our approach leverages monocular video to (1) identify image-space modes from an object's sub-pixel motion, and (2) directly infer spatially-varying Young's modulus and density values from the observed modes. We demonstrate our approach on both simulated and real videos.
   - **Resolution mode:** search
   - **Source paths:**
     - /home/vivekkarmarkar/Python Files/paper-stack-three-test-two/shortlisted/Vibrations/Visual_Vibration_Tomography_Katie_paper_2022.pdf

---
