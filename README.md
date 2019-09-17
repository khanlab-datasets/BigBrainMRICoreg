This dataset includes co-registration of the BigBrain dataset to the MNI PD25 atlas and the ICBM152 2009b atlases.
The data include deformed BigBrain atlases and manual subcortical segmentations in MINC2 and NIFTI-1 formats, as well as relevant spatial transformation in MINC transformation format.
The segmented subcortical structures include: red nucleus, subthalamic nucleus, substantia nigra, caudate, putamen, globus pallidus externa, globus pallidus interna, thalamus, hippocampus

Note that the described improved co-registration was performed upon the BigBrain data in ICBM space from the BigBrain 2015release.

Within this dataset, the down-sampled versions of BigBrain atlases are distributed under the CC BY4.0 License upon the consent from the original data owners, the Montreal Neurological Institute
(Montreal, Canada) and the Forschungszentrum Jülich (Jülich, Germany). However, this exception to the existing BigBrain dataset does not alter the general term of that license for use of the
BigBrain itself, which is still under the CC BY-NC-SA 4.0 License.

The included files are as follows:

1. Deformed BigBrain atlases:
BigBrain in PD25 space: BigBrain-to-PD25-nonlin-{300um, 0.5mm, 1mm}
BigBrain in ICBM152 symmetric atlas: BigBrain-to-ICBM2009sym-nonlin-{300um, 0.5mm, 1mm}
BigBrain in ICBM152 asymmetric atlas: BigBrain-to-ICBM2009asym-nonlin-{300um, 0.5mm, 1mm}
Synthetic T2w PD25 atlas: PD25-SynT2-template-{300um, 0.5mm, 1mm}
T1-T2* fusion PD25 atlas: PD25-enhanceFusion-template-{300um, 0.5mm, 1mm}

2. Manual subcortical segmentations:
BigBrain coregistered to ICBM in the BigBrain2015 release: BigBrain-segmentation-0.3mm
MNI PD25: PD25-segmentation-0.5mm
ICBM152 2009b symmetric: ICBM2009b_sym-segmentation-0.5mm
ICMB152 2009b asymmetric: ICBM2009b_asym-segmentation-0.5mm

3. Related transformations:
BiBrain-to-PD25: BigBrain-to-PD25-nonlin.xfm
BigBrain-to-ICBM2009asym: BigBrain-to-ICBM2009asym-nonlin.xfm
BigBrain-to-ICBM2009sym: BigBrain-to-ICBM2009sym-nonlin.xfm
PD25-to-ICBM2009asym: PD25-to-ICBM2009asym-nonlin.xfm
PD25-to-ICBM2009sym: PD25-to-ICBM2009sym-nonlin.xfm


4. List of subcortical labels: subcortical-labels.csv



References:

For the methods used, please cite the following articles:
1. Y. Xiao, J.C. Lau, T. Anderson,J. DeKraker, D. Louis Collins, T.M. Peters, and A.R. Khan, “Bridging micro and macro:
accurate registration of the BigBrain dataset with the MNI PD25 and ICBM152 atlases,” bioRxiv, 561118, Cold Spring Harbor Laboratory,
doi: https://doi.org/10.1101/561118.

2. Y. Xiao, V. Fonov, S. Beriault, F.A. Subaie, M.M. Chakravarty, A.F. Sadikot,
G. Bruce Pike, and D. Louis Collins, “Multi-contrast unbiased MRI atlas of a
Parkinson's disease population,” International Journal of Computer-Assisted
Radiology and Surgery, vol. 10(3), pp. 329-341, 2015.

3.Y. Xiao, V. Fonov, S. Beriault, F.A. Subaie, M.M. Chakravarty, A.F. Sadikot, G. Bruce Pike, and D. Louis Collins,
“A dataset of multi-contrast population-averaged brain MRI atlases of a Parkinson’s disease cohort,”Data in Brief, 2017.

When using the downsamled BigBrain atlases, please cite the following article:
1. Amunts, K. et al.: “BigBrain: An Ultrahigh-Resolution 3D Human Brain Model”, Science (2013) 340 no. 6139 1472-1475, June 2013
