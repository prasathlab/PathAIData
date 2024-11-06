# Path AI Ready datasets
This repository provides a curated list of publicly available histopathology datasets, accompanied by relevant metadata to facilitate research, analysis, and model development in medical imaging and pathology.

## Purpose
The aim of this repository is to centralize information on diverse histopathology datasets for researchers, data scientists, and healthcare professionals working in fields such as machine learning, computer vision, and biomedical research. Each dataset entry includes detailed information such as:

- Dataset Name: Identifying title for easy reference
- Tissue Type/Organ: Type of tissue or organ examined 
- Staining Method: Type of staining used in images 
- Link: Direct URL to the dataset source for quick access
- Magnification and Scanners: Magnification levels and imaging equipment specifications
- Dataset Size: Number of images, patches, or slides included
- Resolution: Resolution or pixel density of the images
- Collection Method: Type of surgical or imaging procedure used to gather the data
- Patient Information: Number of patients included in the dataset
- Year of Publication: Year when the dataset was made publicly available
  
## Datasets
  
| Dataset Name | Tissue Type/Organ | Staining Method | Link | Magnification and Scanners | Dataset Size | Resolution | Collection Method | Patient Information | Year of Publication |
|--------------|-------------------|-----------------|------|----------------------------|--------------|------------|-------------------|---------------------|----------------------|
| BreakHis | Breast | H&E | [Link](http://www.inf.ufpr.br/vri/databases/BreaKHis_v1.tar.gz) | (Magnification, Benign, Malignant):<br>(40X, 652, 1,370) <br>(100X, 644, 1,437)<br>(200X, 623, 1,390)<br>(400X, 588, 1,232) | (Benign,Malignant,Total)<br>(2480, 5429, 7909) | 700 x 460 pixels | SOB method | 82 | 2017 |
| LC25000 | Lung and colon || [Link](https://academictorrents.com/details/7a638ed187a6180fd6e464b3666a6ea0499af4af) || ./lung_image_sets/lung_aca :     5000<br>./lung_image_sets/lung_n :     5000<br>./lung_image_sets/lung_scc :     5000<br>./colon_image_sets/colon_n :     5000<br>./colon_image_sets/colon_aca :     5000 | 768 x 768 pixels ||| 2019 |
| Ovarian Bevacizumab Response | Ovary | H&E | [Link](https://www.cancerimagingarchive.net/collection/ovarian-bevacizumab-response/) | (Maginification, lense)<br>(20X, Leica AT Turbo, Leica, Germany) | 288 H&E stained WSIs <br>(including 162 effective and 126 invalid WSIs) | 54342 × 41048 in pixels on average | debulking surgery  | 78 | 2022 |
| PLISM(PLISM-original,PLISM-WSI, PLISM- sm) | Various | H&E | [Link](https://plus.figshare.com/articles/dataset/Pathology_Images_of_Scanners_and_Mobilephones_PLISM_-_Original_Whole_Slide_Images_Dataset/24988074)<br>[Link](https://plus.figshare.com/articles/dataset/Pathology_Images_of_Scanners_and_Mobilephones_PLISM_-_Whole_Slide_Images_Dataset/23614422)<br>[Link](https://plus.figshare.com/articles/dataset/Pathology_Images_of_Scanners_and_Mobilephones_PLISM_-_Smartphone_Images_Dataset/23590791) | 400X<br><br>WSI Scanner :<br>NanoZoomer-S360 C13220-01 scanner, NanoZoomer-S210 C13239-01 scanner, NanoZoomer-SQ C13140-D03, NanoZoomer-S60 C13210-01, Aperio AT2, Aperio GT450, Ultrafast Scanner<br><br>Smartphone cameras:<br>Galaxy S20 5G SC-51A, moto g8, Redmi Note9 Pro, iPhone 6, iPhone 13 mini, iTel P33 | PLISM-orginal subset consists of 91 original WSIs before image registration<br>PLISM-WSI: 310,947 (3,417 Aligned Image Groups × 91 WSIs)<br>PLISM-sm: 57,902 (4,454 Aligned Image Groups × 13 devices) | PLISM-original: 0.22 to 0.26 µm/pixel<br>PLISM-WSI: 1024 x 1024 pixels <br>PLISM-sm: 512 x 512 pixels || 46 | 2024 |
| Chaoyang ||| [Link](https://bupt-ai-cz.github.io/HSA-NRL/) | 20X | Training samples: 1111 normal, 842 serrated, 1404 adenocarcinoma, 664 adenoma.<br>Testing samples: 705 normal, 321 serrated, 840 adenocarcinoma, 273 adenoma. | 512×512 pixels ||| 2021 |
| DiagSet | Prostate | H&E | [Link](https://github.com/michalkoziarski/DiagSet) | 40X, 20X, 10X and 5X<br>Hamamatsu C12000-22 digital slide scanner | Over 2.6 million tissue patches extracted from 430 fully annotated scans<br>4675 scans with assigned binary diagnoses<br>46 scans with diagnoses independently provided by a group of histopathologists | 0.25 μm/pixel, 0.50 μm/pixel, 1.0 μm/pixel, and 2.0 μm/pixel ||| 2024 |
| BCNB | Breast<br>(specifically for early breast cancer) | H&E | [Link](https://bupt-ai-cz.github.io/BCNB/) | Iscan Coreo pathologic scanner  <br>200x magnification ||| Core-needle biopsy  | 1058 | 2021 |
| MHIST | Colorectal polyps | H&E | [Link](https://bmirds.github.io/MHIST/) | 40x<br> Aperio AT2 scanner | 3152 | 224 x 224 pixels | Images were extracted from 328 Formalin Fixed Paraffin-Embedded (FFPE) whole-slide images of colorectal polyps || 2021 |
| A histopathological image dataset for grading breast invasive ductal carcinomas | Breast | H&E | [Link](https://data.mendeley.com/datasets/w7jjcx7gj6/1) | 4x, 10x, 20x, and 40x<br>Apple iPhone 7 Plus camera | 922 | 2100 × 1574 and 1276 × 956 pixels || 124 | 2020 |
| Histopathological Image based Skin Cancer Classification Using CNN | Skin | H&E | [Link](https://data.mendeley.com/datasets/d48b5zybck/1) | ×40, ×100, ×200, and ×400<br>Olympus BX63 Digital Motorized Upright Advanced microscope | 16,099 histology images with data augmentation <br>4,357 histology images without data augmentation | 1600 × 1200 pixels || 354 | 2021 |
| Histopathological image patches from colorectal cancer with three classes: tumor, stroma, and other | Colorectal | H&E | [Link](https://data.mendeley.com/datasets/37t2d6xmy2/1) | 0.5 MPP<br>Hamamatsu NanoZoomer-XR  | 2770 image patches | 224 x 224 pixels || 17 | 2023 |
| Histopathological imaging database for Oral Cancer analysis | Oral cavity | H&E | [Link](https://data.mendeley.com/datasets/ftmp4cvtmb/2) | Normal Epithelium:<br>89 images at 100x magnification<br>201 images at 400x magnification<br><br>Oral Squamous Cell Carcinoma (OSCC):<br>439 images at 100x magnification<br>495 images at 400x magnification<br><br>Leica ICC50 HD microscope | 1224 ||| 230 | V1:2019 <br>V2:2023 |
| A histopathological image dataset for endometrial disease diagnosis | Endometrium | H&E | [Link](https://doi.org/10.6084/m9.figshare.7306361.v2) | 10x, 20x<br>Mixotic scanner | 3500 | 640x480 pixels | Hysteroscopic surgery or hysterectomy | 498 | 2017-2018 |
| Multi-class texture analysis in colorectal cancer histology | Colorectal  | H&E | [Link](https://zenodo.org/records/53169) || 5000 | 150 px x 150 px ||| 2016 |
| Invasive Ductal Carcinoma (IDC) Histology Image Dataset | Breast || [Link](https://andrewjanowczyk.com/wp-static/IDC_regular_ps50_idx5.zip) | 40x  | 277,524 patches | 50x50 pixels per patch || 162 | 2015 |
| OvarianCancer&SubtypesDatasetHistopathology | Ovary || [Link](https://data.mendeley.com/datasets/kztymsrjx9/1) |||||| 2021 |
| ViCE Histopathology Images | Intestine | H&E | [Link](https://ieee-dataport.org/documents/vice-histopathology-images#files) |||||| 2024 |
| HEPASS Algorithm Dataset | Liver | H&E | [Link](https://data.mendeley.com/datasets/4mcc9rg4k5/1) || 385 ||| 77 | 2020 |
| RINGS algorithm dataset | Prostate | H&E | [Link](https://data.mendeley.com/datasets/h8bdwrtnr5/1) | 40x | train: 1000 , test: 500 | 1500X1500 ||| 2021 |
| NDB-UFES | Oral | H&E | [Link](https://data.mendeley.com/datasets/bbmmm4wgr8/4) | 10X, 40 X<br>Olympus DP73 microscope, <br>Olympus Standard cellLens | 237 | 2048 x 1536 | Biopsy || 2023 |
| RENFAST algorithm dataset | Kidneys | PAS, TRIC | [Link](https://data.mendeley.com/datasets/m2t49zf6xr/1) | Hamamatsu NanoZoomer S210,<br> 10x magnification | 650 | 512x512 pixels | Biopsy | 65 | 2020 |
| DeepHP Dataset | Gastric Mucosa | H&E | [Link](https://www.lghm.com.br/datasets)<br>[Link](https://www.mdpi.com/1422-0067/23/23/14581) | ZEISS Microscope Axio imager.M2,<br> ×20 magnification | 394,926 patches | 256x256 pixels | Biopsy | 19 | 2022 |
| HistMNIST | Bone Marrow | H&E | [Link](https://zenodo.org/records/1205024) | 40× magnification | 10,800 images | 28x28 pixels | Biopsy | 16 | 2018 |
| Histopathology Imagery Dataset of Ph-negative Myeloproliferative Neoplasm | Bone Marrow || [Link](https://data.mendeley.com/datasets/8mds4wpch3/1) | Olympus BX41 Dual head microscope,<br> x10, x20, x40 lens types | 300 images || Biopsy || 2023 |
| NCT-CRC-HE-100K | colon and rectum | H&E | [Link](https://zenodo.org/records/1214456/files/NCT-CRC-HE-100K.zip?download=1) | 0.5 microns per pixel | 100,000 images | 224x224 pixels | Biopsy | 86 | 2017 |
| NCT-CRC-HE-100K-NONORM | colon and rectum | H&E | [Link](https://zenodo.org/records/1214456/files/NCT-CRC-HE-100K-NONORM.zip?download=1) | 0.5 microns per pixel | 100,000 images | 224x224 pixels | Biopsy | 86 | 2017 |
| CRC-VAL-HE-7K | Colorectal Adenocarcinoma | H&E | [Link](https://zenodo.org/records/1214456/files/CRC-VAL-HE-7K.zip?download=1) | 0.5 microns per pixel | 7,180 images | 224x224 pixels | Biopsy | 50 | 2017 |
|  Histological Image Processing Features Induce a Quantitative Characterization of Chronic Tumor Hypoxia | colon | H&E, anti-pimonidazole | [Link](http://dx.doi.org/10.7910/DVN/SI32FV) | 10x, 20x magnification ||| Biopsy || 2016 |
| UNITOPATHO | Colorectal polyps | H&E | [Link](https://ieee-dataport.org/open-access/unitopatho) | 20x magnification | 9536 patches (292 whole-slide images) | 224x224 pixels | Biopsy | 292 | 2021 |
| Histological images of the leech Hirudo medicinalis | Central nervous system || [Link](https://data.mendeley.com/datasets/bjxkcbbhpx/1) | 3x magnification | 432 images (216 raw, 216 clean) | 3072x4096 px (raw), <br>2800x2800 px (clean) | Dissection | 2 leeches | 2022 |
| H&E-stained oral squamous cell carcinoma histological images dataset | Oral Cavity | H&E | [Link](https://data.mendeley.com/datasets/9bsc36jyrt/1) | 20x magnification | 1,020 images | 640 X 640 px ||| 2022 |
| Gastric Cancer Histopathology Tissue Image Dataset (GCHTID) | stomach | H&E | [Link](https://figshare.com/articles/dataset/Gastric_Cancer_Histopathology_Tissue_Image_Dataset_GCHTID_/25954813) || 31096 non-overlapping images | 224x224 pixels ||| 2024 |
| Enteroscope Biopsy Histopathological H&E Image Dataset (EBHI-Seg) | Colorectal | H&E | [Link](https://figshare.com/articles/dataset/EBHI-SEG/21540159/1) | 400× magnification,<br>Olympus microscope,<br> NewUsbCamera | 4,456 images <br>(2,228 histopathology images and 2,228 ground truth images) | 224x224 pixels | Intestinal biopsy || 2023 |
| Automatic Registration Of Breast Cancer Tissue | Breast tissue | IHC, H&E | [Link](https://acrobat.grand-challenge.org/) || 750 cases for development, <br>100 cases for validation, 200 cases for testing |||| 2023 |
| Automatic Non-rigid Histological Image Registration (ANHIR) Dataset | Various(lesions, lung-lobes, mammary-glands) | Different dyes | [Link](https://anhir.grand-challenge.org/) | High-resolution <br>(up to 40x magnification) || Up to 100k x 200k pixels ||| 2019 |
| ICIAR 2018 BACH Dataset | Breast tissue | H&E | [Link](https://iciar2018-challenge.grand-challenge.org/Dataset/) || 400+ labeled microscopy images, <br>10 pixel-wise labeled, <br>20 non-labeled whole-slide images |||| 2018 |
| BRACS | Breast tissue || [Link](https://www.bracs.icar.cnr.it/details/) | 40x magnification | WSIs: 578 (Training: 395, Validation: 65, Testing: 118) <br>RoIs: 6,758 (Training: 3,657, Validation: 312, Testing: 474) | WSIs: 100,000 x 100,000 pixels,<br>RoIs: 4,000 x 4,000 pixels ||| 2020 |
| CAMELYON16 | Sentinel lymph node || [Link](https://camelyon16.grand-challenge.org/Data/) || 400 WSIs (Training: 270, Testing: 130) |||| 2016 |
| CAMELYON17 | Sentinel lymph node | H&E | [Link](https://camelyon17.grand-challenge.org/) || 1399 WSIs (Training: 1000+, Testing: 399) |||| 2017 |
| CPTAC-BRCA | Breast || [Link](https://doi.org/10.7937/TCIA.CAEM-YS80) || 642 ||| 134 | 2021 |
| DRYAD dataset (hashi) | Breast || [Link](https://datadryad.org/stash/dataset/doi:10.5061/dryad.1g2nt41) | 40x magnification, <br>Aperio and Ventana scanners || Various (scaled images) || 500 | 2018 |
| GTEx Portal | multiple | H&E | [Link](https://gtexportal.org/home/histologyPage) | Various ||| Dissected from the central breast subareolar region of the right breast | 948 patients (multiple slides per patients) ||
| HER2-Warwick dataset | Breast | H&E | [Link](https://warwick.ac.uk/fac/cross_fac/tia/data/her2contest/) || 100 WSIs | 100,000 x 80,000 pixels ||| 2016 |
| HEROHE | Breast | H&E | [Link](https://ecd.p2020.grand-challenge.org) | 3D Histech Pannoramic 1000 |||| 510 | 2022 |
| IMPRESS dataset | Breast | Hematoxylin and Eosin (HE), IHC (PD-L1, CD8+, CD163+) | [Link](https://drive.google.com/drive/folders/1fNf-F_aplm6ACJTWO1vGqbb-DdaP4K_r) | 20x magnification, Hamamatsu scanner |||| 186<br>(HER2+ and TNBC) | 2023 |
| Post-NAT-BRCA | Breast || [Link](https://www.cancerimagingarchive.net/collection/post-nat-brca/) |||||||
| SLN-Breast | Breast, Axillary Lymph Nodes | H&E | [Link](https://www.cancerimagingarchive.net/collection/sln-breast/) | Leica Aperio AT2 scanners at 20x magnification  | 130 ||| 78 | 2019 |
| TCGA-BRCA Dataset | Breast || [Link](https://www.cancerimagingarchive.net/collection/tcga-brca/) ||||| 139 | 2020 |
| TIGER Dataset | Breast | H&E | [Link](https://tiger.grand-challenge.org/Home/) |||||||
| GasHisSDB | Stomach | H&E | [Link](https://gitee.com/neuhwm/GasHisSDB) | Magnification: 20x, <br>Microscopes: Nikon (Japan) and Olympus (Japan) | 245,196 images | Sub-database A: 160×160 pixels,<br>Sub-database B: 120×120 pixels,<br>Sub-database C: 80×80 pixels ||| 2021 |
| MIHIC | Lung   | IHC, H&E | [Link](https://zenodo.org/records/10065510) | Magnification: 40x | 309,698 image patches | 128x128 pixels | Tissue Microarray (TMA) | 114 | 2024 |
| BMIRDS Dartmouth Lung Cancer Histology Dataset | Lung adenocarcinoma | H&E | [Link](https://bmirds.github.io/LungCancer/) | 20x or 40x magnification; <br>Aperio AT2 whole-slide scanner | 143 || Formalin-Fixed Paraffin-Embedded (FFPE) || 2019 |
| BMIRDS Dartmouth Kidney Cancer Histology Dataset | Renal Cell Carcinoma | H&E | [Link](https://bmirds.github.io/KidneyCancer/) | 20x magnification; <br>Aperio AT2 whole-slide scanner | 563 || Formalin-Fixed Paraffin-Embedded (FFPE) || 2021 |
| Gland Segmentation in Colon Histology Images (GlaS) | Colon | H&E | [Link](https://warwick.ac.uk/fac/cross_fac/tia/data/glascontest/) | <br>Zeiss MIRAX MIDI Slide Scanner, <br>20× objective magnification | 165 images  || Formalin-Fixed Paraffin-Embedded (FFPE) | 16 | 2015 |
| ACDC-LungHP | Lung | H&E | [Link](https://acdc-lunghp.grand-challenge.org/) | 3DHISTECH Pannoramic 250, <br>20x objective magnification | 200 slides, 150 training, 50 test |||| 2019 |
| Adipocyte(Count-ception) | skin | H&E | [Link](https://github.com/ieee8023/countception) | 40x | 200 slides | VGG: 256x256, <br>Adipocyte: 150x150 ||| 2017 |
| MBM(countception) | bone | H&E | [Link](https://github.com/ieee8023/countception) | 40x | 44 patches | MBM: 600x600 ||| 2017 |
| ADP | multiple | H&E Mostly | [Link](https://www.dsp.utoronto.ca/projects/ADP/) | 40x,<br>Huron TissueScope LE1.2 | 17,668 patches | 1088x1088 pixels ||||
| AGGC | prostate | H&E | [Link](https://aggc22.grand-challenge.org/AGGC22/) | 20x<br>Subset1 and Subset2: Akoya Biosciences Scanner,<br>Subset3: each specimen is scanned by multiple scanners | 187 prostatectomy and 156 biopsy specimens |||| 2022 |
| Multi-Class Cell Detection Using Spatial Context Representation (BRCA-M2C ) | breast | H&E | [Link](https://drive.usercontent.google.com/download?id=1HvIzsOs5FP9OdlJKAnU_PM6tX4B2Q1rk&export=download&authuser=0) | 20x | 120 patches (Breast), <br>57 patches (Lung), <br>41 patches (Colorectal) |||| 2022 |
| HER2 tumor ROIs | breast | H&E | [Link](https://www.cancerimagingarchive.net/collection/her2-tumor-rois/) | 20x <br>Aperio ScanScope || 512x512 || 273 | 2022 |
| CryoNuSeg | Multiple | H&E | [Link](https://github.com/masih4/CryoNuSeg) | 40x magnification, various scanning centers | 30 WSIs from 10 organs, 7596 nuclei (Annotator 1) | 512 x 512 pixels ||| 2021 |
| Lizard | Colon | H&E | [Link](https://warwick.ac.uk/lizard-dataset) | 20x magnification | 495,179 nuclei in 291 image regions | 1016 x 917 pixels ||| 2021 |
| Pan-tumor T-lymphocyte dataset | Multiple | IHC | [Link](https://zenodo.org/records/7500843) | 40x magnification, <br>NanoZoomer 2.0-HT scanner (Hamamatsu) | 92 tumor samples from 4 tumor indications | 2150 x 2150  | Formalin-Fixed Paraffin-Embedded (FFPE) | 92 | 2023 |
| CoNSeP - HoVer-Net | Colorectal adenocarcinoma | H&E | [Link](https://warwick.ac.uk/fac/cross_fac/tia/data/hovernet/) | 40x<br>Omnyx VL120 scanner | 41 image tiles | 1000 x 1000 pixels | Surgical resection | 16 | 2019 |
| The PANDA challenge | Prostate | H&E | [Link](https://www.kaggle.com/c/prostate-cancer-grade-assessment/data) | Various scanners including 3DHISTECH, Hamamatsu Photonics, and Leica Biosystems | 12,625 biopsies  || Retrospective collection || 2022 |
| PanNuke | multiple | H&E | [Link](https://warwick.ac.uk/fac/cross_fac/tia/data/pannuke) | 40x ||||| 2019 |
| Janowczyk et al. | breast | H&E | [Link](https://andrewjanowczyk.com/use-case-1-nuclei-segmentation/) | 40x | 143 | 2000X2000 ||| 2015 |
| NuCLS | breast | H&E | [Link](https://nucls.grand-challenge.org/) | 40x | 125 |||| 2021 |
| DigestPath2019 - colonoscopy tissue segment  | Colon | H&E | [Link](https://digestpath2019.grand-challenge.org/) | 20X | Train: 660, Test: 212 | 5000X5000 ||| 2019 |
| Bone-Marrow-Cytomorphology | Marrow | May-Grünwald-Giemsa/Pappenheim | [Link](https://www.cancerimagingarchive.net/collection/bone-marrow-cytomorphology_mll_helmholtz_fraunhofer/) | 40X || 250X250 || 945 | 2021 |
| PAIP2021 | Multiple<br>(Colon, Prostate, Pancreas) | H&E | [Link](https://paip2021.grand-challenge.org/Home/) | 20x <br>Aperio AT2 | Train: 150, Valid: 30, Test: 60 |||| 2021 |
| WSSS4LUAD | Lung | H&E | [Link](https://wsss4luad.grand-challenge.org/) | Magnification: 40X, <br>Scanner: Leica GT 450 | 87 (Train: 53, valid: 12, Test: 12) |||| 2022 |
| Cellseg | multiple | multiple | [Link](https://neurips22-cellseg.grand-challenge.org/) | Various scanners | 1,000 patches |||||
| PAIP2023 | multiple organ | H&E | [Link](https://2023paip.grand-challenge.org/) |||||| 2023 |
| NuClick | Lymphocyte | H&E, IHC | [Link](https://warwick.ac.uk/fac/cross_fac/tia/data/nuclick/) || Train: 671, Valid: 200 | patch (256x256) ||| 2020 |
| MIDOG 2022 || H&E | [Link](https://midog2022.grand-challenge.org/) || Train: 405 cases, 9501 mitotic annotation |||| 2022 |
| MIDOG 2021  | Breast | H&E | [Link](https://imig.science/midog2021/the-dataset/) | Scanner 1: Hamamatsu XR nanozoomer 2.0<br>Scanner 2: Hamamatsu S360 (0.5 NA)<br>Scanner 3: Aperio ScanScope CS2<br>Scanner 4: Leica GT450 | 200 wsi: 50 wsi / scanners - 4 scanners |||| 2021 |
| MIDOG++ | multiple <br> (Breast, Lung, Lymph nodes, Skin) | H&E | [Link](https://springernature.figshare.com/collections/MIDOG_A_Comprehensive_Multi-Domain_Dataset_for_Mitotic_Figure_Detection/6615571/1) || 503 images | 0.25 µm/px or 0.23 µm/px | Archived tissue blocks, routine processing steps || 2023 |
| CAMEL | Lymph nodes, Colorectal tissue | H&E | [Link](https://github.com/ThoroughImages/CAMEL) | Magnification: 20x, Scanner: Various | 177 | 0.25 µm/px ||| 2019 |
| OCELOT | Multiple <br> (Bladder, Endometrium, Head-and-neck, Kidney, Prostate, Stomach) | H&E | [Link](https://ocelot2023.grand-challenge.org/ocelot2023/) || 304 | 1024X1024 ||| 2023 |
| CAMELYON | Breast (Lymph node) | H&E | [Link](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6007545/) | Magnification: 240 nm/px, <br><br>Scanners: 3DHistech Pannoramic Flash II 250, <br>Hamamatsu NanoZoomer-XR C12000-01, <br>Philips Ultrafast Scanner | 1399 |||| 2018 |
| BCSS  | Breast | H&E | [Link](https://academic.oup.com/bioinformatics/article/35/18/3461/5307750) || 151 |||| 2019 |
| SegPath | multiple | H&E | [Link](https://www.cell.com/patterns/fulltext/S2666-3899(23)00019-3) | Magnification: 40×, <br>Slide scanner: Hamamatsu Nanozoomer S60 | 158,687 patches || Tissue microarray (TMA), Pathologist annotations | 1583 | 2023 |
| SPIE-AAPM_NCI BreastPathQ | Breast | H&E | [Link](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8107263/) | Magnification: 20×, <br>Slide scanner: Aperio AT Turbo 1757 | 96 WSI scans, 3698 patches | 0.5 μm/pixel || 55 (WSI) 64 (original) | 2018 |
| NADT-Prostate | Prostate | Multiple (H&E, IHC) | [Link](https://www.sciencedirect.com/science/article/pii/S0302283821002074?via%3Dihub) || 141 tumor foci, 110 biopsies ||| 37 | 2021 |
| TCGA-TIL-WSI | Multiple (13) | H&E | [Link](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5943714/) || 5,455 WSIs | 50-micron || ~4,759 | 2018 |
| TUPAC16 - aux | Breast - mitoses | H&E | [Link](https://tupac.grand-challenge.org/Dataset/) | 40x magnification, Leica SCN400  | 500 WSIs (Training), 73 (Mitosis), 148 (ROIs) | 50,000 x 50,000 pixels (WSI) ||| 2017 |
| UniToPatho | Colon | H&E | [Link](https://ieeexplore.ieee.org/document/9506198) | 20x - Hamamatsu Nanozoomer S210 | 9536 patches, 292 WSIs | 224x224 pixels  || 292 | 2021 |
| Artificial intelligence for tumor tissue detection and histological regression grading in esophageal adenocarcinomas (Tolkach Y. et al.) | oesophageal adenocarcinomas | H&E | [Link](https://www.thelancet.com/journals/landig/article/PIIS2589-7500(23)00027-4/fulltext) | 40x - Nanozoomer S360, Leica Aperio series histoscanners | UKK1: 34,704 patches from 22 wsi (20 patients); <br>WNS: 121,642 patches from 62 wsi (15 patients); <br>CHA: 32,796 patches from 214 wsi (69 patients); <br>TCGA:178,187 patches from 22 wsi (22 patients) | 256x256 ||| 2023 |
| VisioMel | Melanoma | H&E | [Link](https://www.drivendata.org/competitions/148/visiomel-melanoma/page/717/) || train: 1342 wsi, test: 600, valid: 1200, 16 WSIs annotated || biopsy || 2023 |
| BreCaHAD | Breast | H&E | [Link](https://figshare.com/articles/dataset/BreCaHAD_A_Dataset_for_Breast_Cancer_Histopathological_Annotation_and_Diagnosis/7379186) | 40x - Zeiss | 162 | 1360 × 1024 pixels | biopsy || 2019 |
| UCSB Bio-Segmentation Benchmark dataset(Gelasca et al.) | Breast | H&E | [Link](https://bioimage.ucsb.edu/research/bio-segmentation) || 50 |||| 2008 |
| PATHVQA | Multiple | Multiple | [Link](https://drive.google.com/drive/folders/1G2C2_FUCyYQKCkSeCRRiTTsLDvOAjFj5) || 4,998 images || Extracted from pathology textbooks, online || 2020 |
| CoNIC 2022 | Colon | H&E | [Link](https://conic-challenge.grand-challenge.org/) | 20× magnification | 4,981 patches  | 256×256 pixels ||| 2022 |
| MoNuSAC 2020 | multiple <br>(Lung, Prostate, Kidney, Breast) | H&E | [Link](https://monusac-2020.grand-challenge.org/) | 40x scanner magnification | 31,000 nuclear annotations |||| 2020 |
| MoNuSeg | multiple (7) | H&E | [Link](https://monuseg.grand-challenge.org/Data/) | 40x scanner magnification | 30 images, 22,000 annotations |||| 2018 |
| ARCH | Multiple | H&E, IHC | [Link](https://warwick.ac.uk/fac/cross_fac/tia/data/arch) | multiple magnification | 4270 |||| 2021 |
| Osteosarcoma-Tumor-Assessment | Bone   | H&E | [Link](https://www.cancerimagingarchive.net/collection/osteosarcoma-tumor-assessment/) | 10X resolution | 1144 | 1024x1024 || 50 | 2019 |
| CoCaHis | Colon | H&E | [Link](https://www.sciencedirect.com/science/article/abs/pii/S1746809420305085) | 10X resolution || 1024x1024 | Intraoperative collection | 19 | 2019 |
| Naylor et al. | Breast | H&E | [Link](https://zenodo.org/records/2579118#.Yt5FWt_RaUk) || 50 ||| 11 ||
| SICAPv2 | Prostate | H&E | [Link](https://data.mendeley.com/datasets/9xxm58dvs3/1) | 40x scanner magnification<br>Ventana iScan Coreo | 155 || biopsy | 95 | 2021 |
| CPTAC-COAD | Colon || [Link](https://www.cancerimagingarchive.net/collection/cptac-coad/) |||| biopsy | 106 | 2021 |
| PAIP2020 | Colon | H&E | [Link](https://paip2020.grand-challenge.org/Dataset/) | 40X magnification <br>Aperio AT2 | Train: 47, Valid: 31, Test: 40 ||| 118 | 2020 |
| KIMIA Path24C | multiple | multiple (IHC, H&E, Masson's trichrome) | [Link](https://arxiv.org/pdf/2102.07611) | 20x -TissueScope LE 1.0. | 28380 | 1000x1000 pixels || 24 | 2021 |
| UPENN-GBM | glioblastoma | H&E | [Link](https://www.cancerimagingarchive.net/collection/upenn-gbm/) | 40x | 71 ||| 34 | 2022 |
| Prostate Fused-MRI-Pathology | Prostate | H&E | [Link](https://www.cancerimagingarchive.net/collection/prostate-fused-mri-pathology/) | 20x magnification<br> Aperio scanner | 32508 || Radical prostatectomy specimens | 28 | 2023 |
| PAIP2019 | Liver | H&E | [Link](https://paip2019.grand-challenge.org/Dataset/) | 20x - Aperio AT2 | Train: 50, Valid: 10, Test: 40 || Resection specimens | 100 | 2019 |
| LYON19 | Multiple (Breast, Colon, Protate) | IHC | [Link](https://lyon19.grand-challenge.org/Data/) | Pannoramic 250Flash II scanner | 441 | 0.24μm/px ||| 2019 |
| DigestPath2019 - signet ring cell | multiple (Gallbladder, Gastric mucosa, Lymph, Breast, Ovary, Pancreas, Lung, Urinary bladder, Abdominal wall nodule, Intestine) | H&E | [Link](https://digestpath2019.grand-challenge.org/Dataset/) | 40x | 127 WSIs (21 positive, 106 negative) | 2000x2000 pixels ||| 2019 |
| UPENN-GBM | glioblastoma | H&E | [Link](https://www.cancerimagingarchive.net/collection/upenn-gbm/) | 40x | 71 ||| 34 | 2022 |
| Multi-Scanner SCC | Skin (Canine) | H&E | [Link](https://zenodo.org/records/7418555) | Aperio ScanScope CS2, NanoZoomer S210,<br> NanoZoomer 2.0-HT, Pannoramic 1000, Aperio GT 450 | 220 |||| 2023 |
| Gleason_CNN | Prostate | H&E | [Link](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/OCYCMP) | 40x - NanoZoomer-XR Digital slide scanner, Hamamatsu || 3100x3100 ||| 2018 |
| MITOS_WSI_CMC | Breast (Canine) | H&E | [Link](https://springernature.figshare.com/collections/Dogs_as_Model_for_Human_Breast_Cancer_A_Completely_Annotated_Whole_Slide_Image_Dataset/4951281/1) | 40x Aperio ScanScope CS2  ||||| 2020 |
| IMP-CRS 2024 | Colorectal | H&E | [Link](https://rdm.inesctec.pt/dataset/nis-2023-008) | 40X <br>2 Leica GT450 WSI scanners | Train 4433 wsi, Test: 900 wsi |||| 2024 |
| CRCHisto | Colon | H&E | [Link](https://warwick.ac.uk/fac/cross_fac/tia/data/crchistolabelednucleihe/) | 20x - Omnyx VL120 (UHCW) || 500x500 ||| 2016 |
| CPTAC-OV | Ovary || [Link](https://wiki.cancerimagingarchive.net/display/Public/CPTAC-OV#70227856bcab02c187174a288dbcbf95d26179e8) | 40x | 222 ||| 102 | 2021 |
| ENDO-AID | Endometrial Carcinoma | H&E | [Link](https://zenodo.org/records/7372187#.Y-C6I4TMKUk) | 0.5um/px - 3DHistech P1000 | 91 || Pipelle biopsies || 2022 |
| TNBC | Breast | H&E | [Link](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8438559)<br>[Link](https://peterjacknaylor.github.io/data/) | 40x - Philips Ultra Fast Scanner | 50 | 512x512 || 11 | 2019 |
| Histology images from uniform tumor regions in TCGA Whole Slide Images(Komura et al.) | Various | H&E | [Link](https://zenodo.org/records/5889558#.YuJHdd_RaUk) || 8736 | 128 x 128 μm to 256 x 256 μm || 7951 | 2021 |
| CRAG | Large intestine  | H&E | [Link](https://github.com/XiaoyuZHK/CRAG-Dataset_Aug_ToCOCO) | 20x, Omnyx VL120 Scanner | 213 | around 1500x1500 || 38 | 2019 |
| DiagSeg | Prostate | H&E | [Link](https://github.com/michalkoziarski/DiagSet) | 5x, 10x, 20x, 40x - Hamamatsu C12000-22 | >2.6M patches (from 430 scans) 430 fully annotated scans,<br> 4675 scans with binary diagnosis,<br> and 46 scans with diagnosis given independently <br>by a group of 9 histopathologists |||| 2021 |
| TUPAC16 | brain | H&E | [Link](https://tupac.grand-challenge.org/TUPAC/) | 40x | 500 |||| 2019 |
| TCGA | Multiple | H&E | [Link](https://portal.gdc.cancer.gov/) || > 11k |||||
| HunCRC | Colorectal | H&E | [Link](https://www.cancerimagingarchive.net/collection/hungarian-colorectal-screening/) | 40x - 3DHistech Pannoramic 1000 | 101,389 patches - 200 wsi  | 512x512 | Retrospective collection | 200 | 2022 |
| TissueNet | Uterine cervix | H&E | [Link](https://www.drivendata.org/competitions/67/competition-cervical-biopsy/page/254/) | MIRAX, Aperio, Hamamatsu | 1,016 WSIs; 5,926 patches | 1200x1200 px ||| 2020 |
| AML-Cytomorphology_LMU  | Blood | Wright's stain | [Link](https://www.nature.com/articles/s42256-019-0101-9)<br>[Link](https://www.cancerimagingarchive.net/collection/aml-cytomorphology_lmu/) | 100x - M8 digital microscope/scanner | 18365 ||| 200 | 2019 |
| CPTAC-AML | Marrow, Blood || [Link](https://www.cancerimagingarchive.net/collection/cptac-aml/) | 40x | 122 ||| 88 | 2020 |
| CRC-TP | CRC | H&E | [Link](https://www.sciencedirect.com/science/article/abs/pii/S136184152030061X?via%3Dihub)<br>[Link](https://warwick.ac.uk/fac/cross_fac/tia/data/crc-tp) || 280k patches (from 20 wsi) |||| 2020 |
| DLBCL-morphology | Lymph Node | H&E and immunohistochemical stain | [Link](https://www.cancerimagingarchive.net/collection/dlbcl-morphology/)<br>[Link](https://pmc.ncbi.nlm.nih.gov/articles/PMC8137959/) | 40x magnification, Aperio AT2 scanner | 52194 patches - 246 images | 224x224 || 209 | 2022 |
| Kumar | multiple | H&E | [Link](https://pubmed.ncbi.nlm.nih.gov/28287963/)<br>[Link](https://drive.google.com/drive/folders/1bI3RyshWej9c4YoRW-_q7lh7FOFDFUrJ) | 40x | Train: 16 (13372 nuclei), test same organ (4130 nuclei): 8,<br> test diff organ (4121 nuclei): 6 | 1000x1000 ||| 2017 |
| SegPC-2021 | Blood | Jenner-Giemsa | [Link](https://segpc-2021.grand-challenge.org/)<br>[Link](https://github.com/dsciitism/SegPC-2021)<br>[Link](https://ieee-dataport.org/open-access/segpc-2021-segmentation-multiple-myeloma-plasma-cells-microscopic-images) || 775 images, Train: 298, Valid: 200, Test: 277 |||| 2021 |
| UMMC ER-IHC Breast Histopathology Whole Slide Image and Allred Score | Breast | ER-IHC | [Link](https://ieee-dataport.org/documents/ummc-er-ihc-breast-histopathology-whole-slide-image-and-allred-score) | 20x, 3DHistech Pannoramic DESK | 37 WSIs | ~80,000 x 200,000 pixels ||| 2023 |
| Benign Breast Tumor Dataset | Breast || [Link](https://zenodo.org/records/5084116) ||||| 83 | 2021 |
| Cytological and histological images of breast cancer | Breast | H&E and immunohistochemical stain | [Link](https://zenodo.org/records/7890874) | 40x || Cytology: 3264x2448 px, <br>Histology: 2048x1536 px ||| 2023 |
| A dataset for nuclei segmentation based on Breast Cancer patients | Breast | H&E | [Link](https://zenodo.org/records/1174343) || 50 ||| 11 | 2018 |
| 2 million histological images of breast cancer tumors with her2 labels | Breast | H&E, HER2 IHC | [Link](https://data.niaid.nih.gov/resources?id=zenodo_8383579) | 40x, Leica Aperio AT2 Scanner | 2,051,877 image patches | 256 x 256 || 504 | 2023 |
| Data from: Computational pathology to discriminate benign from malignant intraductal proliferations of the breast | Breast || [Link](https://datadryad.org/stash/dataset/doi:10.5061/dryad.pv85m) || 116 |||| 2015 |
| Biological Classification of Breast Cancer by Real-Time Quantitative RTPCR: Comparisons to Microarray and Histopathology | Breast || [Link](https://www.omicsdi.org/dataset/geo/GSE2607) || 123 ||| 123 | 2006 |
| The Single-Cell Pathology Landscape of Breast Cancer | Breast || [Link](https://zenodo.org/records/4607374) || 352 / 281 (Total / Survival Data) | 720x720 ||| 2020 |
| BIOGRID CURATED DATA FOR PUBLICATION: Type and duration of exogenous hormone use affects breast cancer histology. ||| [Link](https://thebiogrid.org/175785/publication/) |||||||
| Automated Nuclear Pleomorphism Scoring in Breast Cancer | Breast | H&E | [Link](https://zenodo.org/records/6773626) | 3DHistech P1000 | 118 |||| 2020 |
| unnormalised breast cancer histopathology ||| [Link](https://www.kaggle.com/datasets/sourabhkumar29/unnormalised-breast-cancer-histopathology) |||||||
| Multi-omic machine learning predictor of breast cancer therapy response | Breast | H&E | [Link](https://zenodo.org/records/6337925) || 168 ||| 168 | 2021 |
| Curated Breast Imaging Subset of Digital Database for Screening Mammography | Breast || [Link](https://www.cancerimagingarchive.net/collection/cbis-ddsm/) | DBA, HOWTEK, LUMISYS | 10239 ||| 6671 <br> (but there are only 1,566 actual participants in the cohort) | 2017 |
| Lung Adenocarcinoma Evolution H&E Pathomic Feature Analysis Dataset | Lung | H&E | [Link](https://data.mendeley.com/datasets/7zc56ttd96/1) || 162 slides, 669 ROIs ||| 98 | 2023 |
| Fused Radiology-Pathology Lung Dataset | Lung || [Link](https://www.cancerimagingarchive.net/collection/lung-fused-ct-pathology/) || 11210 ||| 6 | 2018 |
| Colsanitas dataset | Breast | H&E | [Link](https://www.nature.com/articles/s41598-022-19278-2) | 40X, Roche iScan HT | 2250(600 normal tissues,<br>250 benign lesions, <br>250 in situ carcinoma,<br>and 1150 invasive carcinoma) | 2048X1536 pixels || 80 | 2022 |
| CPM-17 | brain | H&E | [Link](https://drive.google.com/drive/folders/1sJ4nmkif6j4s2FOGj8j6i_Ye7z9w0TfA)<br>[Link](https://pmc.ncbi.nlm.nih.gov/articles/PMC6454006/#_ad93_) | 20x, 40x  | Train: 32, test: 32 | 500x500 to 600x600 ||| 2019 |
| CPM-15 | brain | H&E | [Link](https://drive.google.com/drive/folders/11ko-GcDsPpA9GBHuCtl_jNzWQl6qY_-I) | 20x, 40x  | 15 (2905 nuclei) | 400x400, 600x1000 ||||
| International Cancer Genome Consortium  Breast Cancer Histology Images | Breast | H&E | [Link](https://ega-archive.org/datasets/EGAD00010001911) || 151 |||| 2016 |
| CRC-ICM | Colon, Rectum | IHC, H&E | [Link 1](https://arxiv.org/pdf/2308.10033)<br>[Link 2](https://data.mendeley.com/datasets/h3fhg9zr47/1) | 200x, 20x magnification | 1,756 images | 4140 x 3096<br>2070 x 1548<br>1280 x 960 || 136 | 2023 |
