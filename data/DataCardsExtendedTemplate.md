# Dataset Name (Acronym)
We will be working with a preprocessed dataset of Caltech-UCSD Birds from 2000-2011. The dataset. The dataset contains high and low dimensional pictures of birds, along with pre-trained text embeddings for training text-to-image synthesis. The data contains images in pickle format of 64x64x3 birds, and 256x256x3 birds. We also have pre trained test embeddings designed to encode descriptive captions, providing conditional inputs for text-to-image synthesi models. This dataset has a variety of birds from different species. The pictures also vary in color, angle, and environment. This will be great for seeing if our model has any issues with mode collapse. The images come with no metadata, meaning we won't have any privacy concerns with it linking to any entity. Overall, we have a simple yet effective dataset in which our model will be trained on.
#### Dataset Link
<!-- info: Provide a link to the dataset: -->
<!-- width: half -->
Dataset Link
The dataset is publicly available at https://www.kaggle.com/datasets/vishalkundar/gandata20/dataLinks to an external site..
#### Data Card Author(s)
<!-- info: Select **one role per** Data Card Author:

(Usage Note: Select the most appropriate choice to describe the author's role
in creating the Data Card.) -->
<!-- width: half -->
- **Harish Lakshman** (Owner / Contributor / Manager)

- **Anthony Lee** (Owner / Contributor / Manager)

- **Daniel Gallegos** (Owner / Contributor / Manager)

- **Rizwan Islam** (Owner / Contributor / Manager)

- **Kanchon Bishnu** (Owner / Contributor / Manager)

- **Neelam Patidar** (Owner / Contributor / Manager)

- **Yug Kalubhai patel** (Owner / Contributor / Manager)

- **Sai Alekhya** (Owner / Contributor / Manager)


## Authorship
### Publishers
#### Publishing Organization(s)
<!-- scope: telescope -->
<!-- info: Provide the names of the institution or organization responsible
for publishing the dataset: -->
Harish Lakshman

Anthony Lee

Daniel Gallegos

Rizwan Islam

Kanchon Bishnu

Neelam Patidar

Yug Kalubhai patel

Sai Alekhya

#### Industry Type(s)
<!-- scope: periscope -->
<!-- info: Select **all applicable** industry types to which the publishing
organizations belong: -->
- Academic - Tech


#### Contact Detail(s)
<!-- scope: microscope -->
<!-- info: Provide publisher contact details: -->
- **Publishing POC: Listed Above** 
- **Affiliation: California State University Los Angeles** 
- **Contact: anthlee494@gmail.com** 


## Dataset Owners


#### Contact Detail(s)
<!-- scope: periscope -->
<!-- info: Provide pathways to contact dataset owners: -->
- **Dataset Owner(s): Vishal Kundar** 
- **Affiliation: CMR Institute Of Technology** 
- **Contact: vishalkundar on kaggle** 

## Dataset Overview
#### Data Subject(s)
<!-- scope: telescope -->
<!-- info: Select ***all applicable**** subjects contained the dataset: -->
- Data: Bird Images


#### Dataset Snapshot
<!-- scope: periscope -->
<!-- info: Provide a snapshot of the dataset:<br><br>(Use the additional notes
to include relevant information, considerations, and links to table(s) with
more detailed breakdowns.) -->
Category | Data
--- | ---
Size of Dataset | 8855
Number of Instances | 8855
Number of Fields | 3
Labeled Classes | 8855
Number of Labels | 200

**Above:** 8855 Bird Images with embeddings, not sure if embeddings obtainable yet

#### Descriptive Statistics
<!-- width: full -->
<!-- info: Provide basic descriptive statistics for each field.

Use additional notes to capture any other relevant information or
considerations.

Usage Note: Some statistics will be relevant for numeric data, for not for
strings. -->



### Sensitivity of Data
#### Sensitivity Type(s)
<!-- scope: telescope -->
<!-- info: Select ***all applicable*** data types present in the dataset: -->

- Anonymous Data

### Dataset Version and Maintenance
#### Maintenance Status
<!-- scope: telescope -->
<!-- info: Select **one:** -->


**Limited Maintenance** - The data will not be updated,
but any technical issues will be
addressed.


#### Version Details
<!-- scope: periscope -->
<!-- info: Provide details about **this** version of the dataset: -->
**Current Version:** 1.0

**Last Updated:** 04/2025

**Release Date:** 04/2025




## Example of Data Points
#### Primary Data Modality
<!-- scope: telescope -->
<!-- info: Select **one**: -->
- Image Data
- Text Data

#### Sampling of Data Points
<!-- scope: periscope -->
<!-- info: Provide link(s) to data points or exploratory demos: -->
![image](https://github.com/user-attachments/assets/fc7809d5-3654-46e6-9129-7fc486c6a7b9)



## Motivations & Intentions
### Motivations
#### Purpose(s)
<!-- scope: telescope -->
<!-- info: Select **one**: -->
- Building GAN model

#### Domain(s) of Application
<!-- scope: periscope -->
<!-- info: Provide a list of key domains of application that the dataset has
been designed for:<br><br>(Usage Note: Use comma-separated keywords.) -->
For example: `Machine Learning`, `Neural Networks`, `Image Generation`.



#### Motivating Factor(s)
<!-- scope: microscope -->
<!-- info: List the primary motivations for creating or curating this dataset:

(Usage Note: use this to describe the problem space and corresponding
motivations for the dataset.) -->
For example:

- The expected outcome of this project is a model that can generate high quality and diverse synthetic images of birds. By generating synthetic bird images, we can contribute to enhancing datasets for species identification, create realistic visuals for media, etc. A potential challenge is the instability of GAN training and the computational resources required, which may need us to look into a pre-trained model.


### Intended Use
#### Dataset Use(s)
<!-- scope: telescope -->
<!-- info: Select **one**: -->
- Safe for research use

  
