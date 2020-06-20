Imaging Data Description
All BraTS multimodal scans are available as NIfTI files (.nii.gz) and describe a) native (T1) and b) post-contrast T1-weighted (T1Gd), c) T2-weighted (T2), and d) T2 Fluid Attenuated Inversion Recovery (FLAIR) volumes, and were acquired with different clinical protocols and various scanners from multiple (n=19) institutions, mentioned as data contributors here.

All the imaging datasets have been segmented manually, by one to four raters, following the same annotation protocol, and their annotations were approved by experienced neuro-radiologists. Annotations comprise the GD-enhancing tumor (ET — label 4), the peritumoral edema (ED — label 2), and the necrotic and non-enhancing tumor core (NCR/NET — label 1), as described in the BraTS reference paper, published in IEEE Transactions for Medical Imaging (also see Fig.1). The provided data are distributed after their pre-processing, i.e. co-registered to the same anatomical template, interpolated to the same resolution (1 mm^3) and skull-stripped.

Comparison with Previous BraTS datasets
The BraTS data provided since BraTS'17 differs significantly from the data provided during the previous BraTS challenges (i.e., 2016 and backwards). The only data that have been previously used and will be utilized again (during BraTS'17-'18) are the images and annotations of BraTS'12-'13, which have been manually annotated by clinical experts in the past. The data used during BraTS'14-'16 (from TCIA) have been discarded, as they described a mixture of pre- and post-operative scans and their ground truth labels have been annotated by the fusion of segmentation results from algorithms that ranked highly during BraTS'12 and '13. This year, expert neuroradiologists have radiologically assessed the complete original TCIA glioma collections (TCGA-GBM, n=262 and TCGA-LGG, n=199) and categorized each scan as pre- or post-operative. Subsequently, all the pre-operative TCIA scans (135 GBM and 108 LGG) were annotated by experts for the various glioma sub-regions and included in this year's BraTS datasets.


Labels information

The labels in the provided data are: 1 for NCR & NET, 2 for ED, 4 for ET, and 0 for everything else.

