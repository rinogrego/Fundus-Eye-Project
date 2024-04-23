# Fundus Eye Project

I just tempted to create a repository to store various information regarding datasets and problems related with fundus (eye). I plan to experiment on various image processing, machine learning, or deep learning methods or techniques that I learnt using fundus data as a starter for experimentation. Good start for learning IMO.

## Datasets

| Name | Size | Diseases | Source |
| -- | -- | -- | -- |
| Diabetic Retinopathy Detection | 1000 / 88.29 GB | Diabetic Retinopathy  | [link](https://www.kaggle.com/c/diabetic-retinopathy-detection/data) |
| Glaucoma Fundus Imaging Datasets (Usability 8.24) | ~2500 / 10.07 GB | Glaucoma | [link](https://www.kaggle.com/datasets/arnavjain1/glaucoma-datasets) |
| SMDG, A Standardized Fundus Glaucoma Dataset (Usability 10.0) | 12.449 / 3.18 GB | Glaucoma | [link](https://www.kaggle.com/datasets/deathtrooper/multichannel-glaucoma-benchmark-dataset) |
| 1000 Fundus images with 39 categories (Usability 6.88) | 1000 / 447.42 MB | 38 diseases | [link](https://www.kaggle.com/datasets/linchundan/fundusimage1000) |
| Dataset for different eye disease (Usability 6.25) | 9824 / 2.82 GB | Glaucoma | [link](https://www.kaggle.com/datasets/dhirajmwagh1111/dataset-for-different-eye-disease) |
| Glaucoma Classification Datasets (Usability 5.63) | 9005 / 2.51 GB | Glaucoma | [link](https://www.kaggle.com/datasets/ayush02102001/glaucoma-classification-datasets) |
| Retina Fundus Image Registration (Usability 9.38) | 129 / 501.29 MB | - | [link](https://www.kaggle.com/datasets/andrewmvd/fundus-image-registration) |
| Ocular Disease Recognition / ODIR-5K (Usability 8.24) | 5000 / 2.03 GB | Normal, Diabetes, Glaucoma, Cataract, Age related Macular Degeneration, Hypertension, Pathological Myopia, Other diseases/abnormalities | [link](https://www.kaggle.com/datasets/andrewmvd/ocular-disease-recognition-odir5k) |
| Retinal Fundus MultiDisease Image Dataset (RFMiD) | 3200 / - | 45 diseases | [link](https://paperswithcode.com/dataset/retinal-fundus-multidisease-image-dataset) [link](https://riadd.grand-challenge.org/download-all-classes/) |
| Retinal Fundus Multi-Disease Image Dataset (RFMiD) 2.0 | 860 / - | 24 diseases | [link](https://zenodo.org/records/7505822) |
| INSPIRE-AVR | 40 / 80 MB | Hypertensive Retinopathy | [link](https://medicine.uiowa.edu/eye/inspire-datasets) [paper](https://www.mdpi.com/2306-5354/11/1/56) | 
| VICAVR | 58 / - | Hypertensive Retinopathy | [link](http://www.varpa.es/research/ophtalmology.html#vicavr) [paper](https://www.mdpi.com/2306-5354/11/1/56) | 
| STARE | 400 / - | Emboli, BRAO, VRAO, BRVO, CRVO, Hemi-CRVO, BDR/NPDR, PDR, ASR, HTR, CNV ([source](https://cecas.clemson.edu/~ahoover/stare/diagnoses/diagnoses.html)) | [link](https://cecas.clemson.edu/~ahoover/stare/) |
| VietAI Advance Course - Retinal Disease Detection | 3785 / 66.54 MB | opacity, diabetic retinopathy, glaucoma, macular edema, macular degeneration, and retinal vascular occlusion | [link](https://www.kaggle.com/competitions/vietai-advance-retinal-disease-detection-2020/data) |
| Sydney Innovation Challenge 2019 | 14145 / 18.07 GB | Diabetic Retinopathy | [link](https://www.kaggle.com/competitions/innovation-challenge-2019/data) |
| William Hoyt | 850 / - | Papilledema, pseudo-papilledema, and various other eye disease groups | [link](https://novel.utah.edu/collection/william-f-hoyt/#tab-collection) |
| PAPILA | 488 / 563.49 MB | Glaucoma | [link](https://figshare.com/articles/dataset/PAPILA/14798004) [paper](https://www.nature.com/articles/s41597-022-01388-1) |
| Retinal Fundus Images (Usability 3.13) | 21746 / 2.49 GB | AMD, Glaucoma, Diabetic Retinopathy, Cataract, Hypertensive Retinopathy, Pathological Myopia | [link](https://www.kaggle.com/datasets/kssanjaynithish03/retinal-fundus-images) |
| Retinal fundus images for glaucoma analysis: the RIGA dataset | 750 / 12.9 GB | Glaucoma | [link](https://deepblue.lib.umich.edu/data/concern/data_sets/3b591905z?locale=en) |
| The SUSTech-SYSU dataset for automated exudate detection and diabetic retinopathy grading | 1151 / 481.69 MB | Diabetic Retinopathy | [link](https://figshare.com/articles/dataset/The_SUSTech-SYSU_dataset_for_automated_exudate_detection_and_diabetic_retinopathy_grading/12570770/1) |
| MuReD | 2208 / 3.83 GB | 19 diseases | [link](https://ieee-dataport.org/documents/multi-label-retinal-disease-mured-dataset) [link](https://data.mendeley.com/datasets/pc4mb3h8hz/1) |

While creating this, I found a paper that have compiled and analyzed various fundus datasets [here](https://www.mdpi.com/2077-0383/12/10/3587).

- Krzywicki, T.; Brona, P.; Zbrzezny, A.M.; Grzybowski, A.E. A Global Review of Publicly Available Datasets Containing Fundus Images: Characteristics, Barriers to Access, Usability, and Generalizability. J. Clin. Med. 2023, 12, 3587. https://doi.org/10.3390/jcm12103587

**Note**: it seems there already exist some works of compiling fundus dataset from various sources, so there may be some duplications if every datasets available are used directly.

## Methods

### Image Preprocessing Techniques

- Augmentation techniques suitable for fundus images (???)
- CLAHE

### Models

- Convolutional Neural Networks
- Transfer Learning
- Convolutional Neural Networks + Machine Learning Models
- Vision Transformer

### Nice Papers to Check
- Attention Based Glaucoma Detection: A Large-scale Database with a CNN Model (2019)
- Hierarchical Vision Transformer using Shifted Windows (2021)
- Multi-Disease Detection in Retinal Imaging based on Ensembling Heterogeneous Deep Learning Models (2021)
- Multi-label Retinal Disease Classification Using Transformers (2022)
- An interpretable transformer network for the retinal disease classification using optical coherence tomography (2023)
- Multi-label classification of retinal disease via a novel vision transformer model (2024)
- Automatic Detection and Classification of Hypertensive Retinopathy with Improved Convolution Neural Network and Improved SVM (2024)
