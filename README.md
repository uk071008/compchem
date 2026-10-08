# Intresting databases

Name | year | Info | # molecules | properties | link
--- | --- | --- | --- | --- | --- 
VQM24 | 2025 | small organic and inorganic molecules, DFT DMC | 836k | thermal, electronic, vibrational, wavefunction | https://zenodo.org/records/15442257
QMspin | 2020 | carbenes singlet, triplet state | 13k | spin gaps | https://archive.materialscloud.org/records/n5m0g-vyd98
tmQM | 2020 | transition metal-organic compound space. organic ligands and 30 transition metals. closed-shell. DFTB(GFN2-xTB). DFT(TPSSh-D3BJ/def2-SVP) | 86k | molecular size, stoichiometry, and metal node degree. electronic and dispersion energies, HOMO and LUMO orbital energies, HOMO-LUMO gap, dipole moment, and natural charge of the metal center. polarizabilities |  https://github.com/bbskjelstad/tmqm
QM9-OR | 2024 | geometry is optimized using density functional theory, and the calculated specific rotations at three wavelengths using CAM-B3LYP/6-31G. number of chiral centers and the absolute configurations. | 121k | chiral centers, calculated optical rotations at 355 nm, 589.3 nm, and 633 nm. | https://zenodo.org/records/13380412
QMOF | 2021 | experimentally synthetizied molecules, calculated properties | 14k | bandgap, DOS, total energy, magnetic momemnt, spin density, PLD, LCD | https://figshare.com/articles/dataset/QMOF_Database/13147324
nmrshiftdb2 | 2021 | At the time of this writing we restrict the type of calculated spectra which are allowed in nmrshiftdb2 to those calculated by so called ab initio methods, as opposed to semi-empirical and other methods, like HOSE code based or neural network based methods. | 396k | The parameters used by nmrshiftdb2 to characterize the calculation parameters by which spectrum and molecular geometry have been calculated are:Program (example value: Gaussian98).Means "Quantum Chemical Program". The computer program by which the calculation has been performed (e. g. Gaussian 98)NMRMethod (example value: GIAO).A methods described in the literature by which the Magnetic shielding tensors are calculated (e.g. GIAO for Gauge Independent Atomic Orbitals or CSGT for Continuous Set of Gauge Transformations) GeomModel (example value: B3LYP) The model chemistry used for the geometry optimization, like RHF for Restricted Hartree Fock or B3LYP for Becke's frequentyl used DFT parameter functional. GeomBasisSet (example value: 6-31G(d)) The basis set used for the geometry optimization, like 6-31G(d).NMRModel (example value: B3LYP).The model chemistry used for the shielding tensor calculation (possible values like in GeomModel).NMRBasisSet (example value: 6-31G(d)).The basis set used for the shielding tensor calculation (possible values like in GeomBasisSet).NMRStandard (example value: TMS).Ab Initio calculations of magnetic properties yield shielding tensors, which are absolute physical quantities, whereas experimental spectra yield so called NMR chemical shifts which are given relative to the resonance frequencies of a given standard compound (usually Tetramethylsilane, TMS). Isotropic shielding values obtained by an ab initio calculation thus need to be subtracted from the isotropic shielding values obtained for a reference compound (usually also TMS). The calculation for the reference compound needs to be performed under exactly the same calculation conditions that have been used for the actualy compound in question. | https://sourceforge.net/projects/nmrshiftdb2/files/data/
AroCageDB | ? | Ligands. Pockets. Aromatic Cages. The geometric descriptors of aromatic binding sites, namely pocket depth, volume, hydrophobicity, and druggability score, were calculated with DoGSiteScorer, a grid-based program that uses a Difference of Gaussians algorithm for pocket detection and a support vector machine model for druggability assessment. Volkamer, A. et al. J. Chem. Inf. Model. 2010, 50 (11), 2041–2052; Volkamer, A. et al. J. Chem. Inf. Model. 2012, 52 (2), 360–372. | 1.5k Complexes 1k ligands | Mol. Weight,	Heavy Atoms, 
Charge,	Is Chiral, logP, HBD, HBA, TPSA, #Bonds, #Rotatable Bonds, Shape Complexity| https://next-gen.materialsproject.org/api
Acrylate Monomer Database | 2026 | | 1.2k monomers 700 generated monomers| canonical SMILES representations, van der Waals volume, static polarizability, and predicted refractive index values ranging across 1.15 to 1.83 | [https://conservancy.umn.edu/bitstreams/07933899-4fc5-4fc9-a170-76dbbf0ba2f9/download ](https://conservancy.umn.edu/items/c5e1e305-4c3c-4a48-9493-87127209324d) |
OpenGEM26 | 2026 | composed of H, C, N, O, S and Cl with up to ten heavy atoms. All calculations are carried out at the ${\omega}$B97X-D/Def2-SVP and Def2-TZVP levels | 200k | trajectories bond length bond angle | https://arxiv.org/abs/2607.21369











