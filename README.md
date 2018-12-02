### NIH_Marmoset_Atlas_v1 (focus on cortical parcellation)
If you used the atlas, please cite: A digital 3D atlas of the marmoset brain based on multi-modal MRI. Liu C, Ye FQ, Chern-Chyi Yen C, Newman JD, Glen D, Leopold DA, Silva AC. Neuroimage. 2017 Dec 2. pii: S1053-8119(17)31018-2. doi: 10.1016/j.neuroimage.2017.12.004. [Epub ahead of print] https://www.ncbi.nlm.nih.gov/pubmed/29208569

Audioslides: http://audioslides.elsevier.com//ViewerLarge.aspx?source=1&doi=10.1016/j.neuroimage.2017.12.004

# Release v1.1 update
This is a major update of our previous (first) release (v0.02) of the NIH marmoset Brain atlas. Updates include:
1) As we will release another atlas (V2) that focus on the white matter pathways soon, we renamed all files of V1 to keep a consistency with our future atlases.
2) We adopted the same number indices for left and right brain regions. To select the left/right ROIs, we provided left/right brain masks.
3) We corrected errors identified in the subcortical regions, including removing the septum, revising and correcting the boundaries of subcortical regions. Note that the subcortical ROIs is still a beta version, as the V1 atlas mainly focused on the cortical parcellation. In the future, we may release a more fine-grained subcortical gray matter ROIs.
4) We added the Caret cortical surface files (beta version). However, This is not completed yet and many features will be added (for example flat maps) in the future.
5) We added a folder to include the results of studies that used the NIH marmoset Brain atlas (V1).


# Release v1.1 files
NIH_cortex_vL_150um.nii.gz -- the location-based parcellation (13 cortical regions)
NIH_cortex_vM_150um.nii.gz -- the MRI-based parcellation (54 cortical regions)
NIH_cortex_vH_150um.nii.gz -- the connectivity-based parcellation (103 cortical regions)
NIH_cortex_vPaxinos_150um.nii.gz -- the Paxinos brain atlas parcellation in NIH MRI template space
NIH_subcortical_beta_150um.nii.gz -- the subcortical ROIs, this is a beta version.
NIH_mask_150um.nii.gz -- whole brain mask
NIH_mask_left_150um.nii.gz -- left brain mask
NIH_mask_right_150um.nii.gz -- right brain mask
Template_sym_xx.nii.gz -- Multi-modal MRI templates
(Template_sym_FADEC.nii.gz is color-coded image and can be viewed by FSLView of the FSL and the mrview of Mrtrix3)
NIH_labels_cortex_and_subcortical.xlsx -- label file for the three NIH atlases and Paxinos atlas parcellations
A digital 3D atlas of the marmoset brain based on multi-modal MRI -- the pre-print manuscript about the atlas
Caret_surface_beta -- this is the beta version of Caret cortical surface file in our template space
Results_On_The_Template_Space -- Studies that used the NIH Marmoset Brain atlas V1. Result files are in the template space.


# Note:
If you are an AFNI user, why bother to download the atlas from here. AFNI has already integrated the whole atlas set (V1) (via command @Install_NIH_Marmoset).
If you are learning AFNI and have questions about the atlas in the AFNI, please feel free to contact me (cirong.liu@nih.gov) or Glen Daniel (glend@mail.nih.gov).
If you have questions about the NIH Marmoset Brain Atlas Project, please contact Dr. Cirong Liu (cirong.liu@nih.gov) or Dr. Afonso Silva (silvaa@ninds.nih.gov)
If you identified errors in the atlas or want to submit your parcellation results to our atlas, please contact Dr. Cirong Liu (cirong.liu@nih.gov).
Thanks for your supporting!
