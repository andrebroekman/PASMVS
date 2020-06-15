# ShinySMVS

## Abstract
A photorealistic, synthetic dataset is presented, consisting of 400 scenes and 18,000 model renderings together with ground truth depth maps, camera intrinsic and extrinsic parameters, and binary segmentation masks. Every scene is rendered from 45 different camera views in a circular pattern, using Blender’s path-tracing rendering engine. Every scene is composed from a unique combination of two camera focal lengths, four 3D models of varying geometrical complexity, five high definition, high dynamic range environmental textures to replicate photorealistic lighting conditions and ten materials. The material properties are primarily specular, with a selection of more diffuse materials for reference. The combination of highly specular and diffuse material properties increases the reconstruction ambiguity and complexity for multi-view stereopsis (MVS) reconstruction algorithms and pipelines, and more recently, state-of-the-art architectures based on neural network implementations. ShinySMVS, originally inspired by the [BlendedMVS dataset](https://github.com/YoYo000/BlendedMVS), serves as an addition to the wide spectrum of available image datasets employed in computer vision research, improving the precision required for novel research applications.

The original ShinySMVS journal article can be downloaded directly from the open access [Data in Brief journal website](https://www.journals.elsevier.com/data-in-brief). The low-resolution (576p) ShinySMVS dataset can be obtained from the [Mendeley data repository](https://www.journals.elsevier.com/data-in-brief). The high-resolution dataset (1536p) can be downloaded from  
[Google Drive](https://drive.google.com/drive/folders/1CRGy5Q0VERUIxS_tlzKp54UTlF36mMiG?usp=sharing); download all 10 part files (total size: 131 Gb) and unzip into a single directory.

![Collage of different scene configurations](https://github.com/andrebroekman/ShinySMVS/blob/master/splash.jpg)

## Data Structure
A total of 400 scene files are provided, each containing a sub-folder for the rendered images files (45 per scene folder), camera properties and binary segmentation masks and rendered depth maps (PFM file format, see [BlendedMVS GitHub page](https://github.com/YoYo000/BlendedMVS)). The scene files are configured in a 85%-15% test train split with the appropriate scene folder names stored in text files in the root directory.

## Author
The ShinySMVS repository is maintained by André Broekman in conjunction with the [Department of Civil Engineering, University of Pretoria](https://www.up.ac.za/civil-engineering), South Africa. Feel free to get in touch via [LinkedIn](https://www.linkedin.com/in/broekmanandre/), [ResearchGate](https://www.researchgate.net/profile/Andre_Broekman) or [Twitter](https://twitter.com/BroekmanAndre).
