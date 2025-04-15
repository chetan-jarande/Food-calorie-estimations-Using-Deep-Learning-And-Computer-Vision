# Food Calorie Estimations Using Deep Learning And Computer Vision

[![GitHub stars](https://img.shields.io/github/stars/chetan-jarande/Food-calorie-estimations-Using-Deep-Learning-And-Computer-Vision)](https://github.com/chetan-jarande/Food-calorie-estimations-Using-Deep-Learning-And-Computer-Vision/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/chetan-jarande/Food-calorie-estimations-Using-Deep-Learning-And-Computer-Vision)](https://github.com/chetan-jarande/Food-calorie-estimations-Using-Deep-Learning-And-Computer-Vision/network/members)

## Table of Contents
- [Food Calorie Estimations Using Deep Learning And Computer Vision](#food-calorie-estimations-using-deep-learning-and-computer-vision)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Dataset Information](#dataset-information)
  - [Code and Usage](#code-and-usage)
  - [Project Report and Papers](#project-report-and-papers)
  - [Extra Components](#extra-components)
  - [Attribution \& Academic Use](#attribution--academic-use)
  - [Contributors](#contributors)
  - [License](#license)
  - [Contact](#contact)

## Overview
This repository contains a project that estimates food calories using deep learning and computer vision techniques. It implements object detection models using both YOLOv4 and YOLOv5, offering practical insights into building and training these models.

## Dataset Information
- **Custom Datasets:**
  You can use your own dataset by uploading it to Google Drive and mounting the drive in your notebook.
- **Roboflow Integration:**
  Create an account on [Roboflow](https://app.roboflow.com) and upload your dataset under **Workspace -> Project -> Your_Dataset**. Adjust the necessary variables (workspace, project, private key) in the notebooks.
- **Notebooks for Training:**
  - **YOLOv4:** Use [`Train_Custom_YOLOv4_Darknet_Roboflow.ipynb`](Extra_components/Training_Custom_YOLOV4/Train_Custom_YOLOv4_Darknet_Roboflow.ipynb)
  - **YOLOv5:** Use [`CJ_Roboflow_Train_Custom_YOLOv5.ipynb`](Extra_components/Training_Custom_YOLOV5/CJ_Roboflow_Train_Custom_YOLOv5.ipynb)
- **Dataset Access:**
  View & download dataset from: [My Roboflow Dataset](https://app.roboflow.com/chetan-projects-object-detcions/fruits--and-thumb-detection)

## Code and Usage
- Main implementation notebook: [`Food calorie estimations Using Deep Learning And Computer Vision.ipynb`](Food_calorie_estimations_Using_Deep_Learning_And_Computer_Vision.ipynb)

## Project Report and Papers
- **Project Report:** [Project Report of Food calorie estimations Using Deep Learning And Computer Vision.pdf](Project_Report_of_Food_calorie_estimations_Using_Deep_Learning_And_Computer_Vision.pdf)
- **Presentation:** [Food Calorie Estimation BE Project PPT](Food_Calorie_Estimation_BE_Project_PPT.pptx)
- **Research Papers:**
  1. [SURVEY ON FOOD CALORIE ESTIMATION USING DEEP LEARNING AND COMPUTER VISION](https://www.jetir.org/view?paper=JETIR2201196)
  2. [Food Calorie Estimation Using Deep Learning and Computer Vision](https://www.jetir.org/view?paper=JETIR2205411)

## Extra Components
This folder contains additional resources including configuration files and extra notebooks:
- **Custom YOLOv4 (Darknet):**
  - [Path To Code file](Extra_components/Training_Custom_YOLOV4)
  - Weights and config files for training a custom YOLOv4 model.
  - [Download YOLOv4 Weights](https://drive.google.com/drive/folders/13kAvdJRTdD1-EBWndrdziyN0sXqczoZU?usp=sharing)
- **Custom YOLOv5:**
  - [Path to code files](Extra_components/Training_Custom_YOLOV5)
  - YOLOv5s V1 model suitable for Android applications.
  - [Download YOLOv5 Weights](https://drive.google.com/drive/folders/12IOvg1eU-9oRnF83e-vHamzejxHdRUGa)
  - [YOLOv5 Folder](https://drive.google.com/drive/folders/1ntILxD9NemhOSQvrB7hI2VFTNlqD0pcb?usp=sharing)
- **Additional Links:**
  See the [`links.txt`](Extra_components/links.txt) file for more details.

## Attribution & Academic Use
If you are using this project for academic purposes—such as incorporating it into a final year project—it is **mandatory** that you provide clear and proper attribution. You must:
- Acknowledge that the project is originally developed by **Chetan Jarande, Mukta Bhagwat, Vishakha Patil, and Diya Ukirde**.
- Include a statement that the work is based on the open-source project available on [GitHub](https://github.com/chetan-jarande/Food-calorie-estimations-Using-Deep-Learning-And-Computer-Vision) and that you are using it with modifications (if any).
- **Not claim the project as entirely your own original work.**
Failure to adhere to these conditions violates both the project’s license and academic integrity standards.

## Contributors
**Made  With 💖 by**
- **Chetan Jarande**
- **Mukta Bhagwat**
- **Vishakha Patil**
- **Diya Ukirde**

## License
This project is licensed under the [Creative Commons Attribution-NonCommercial 4.0 International License](LICENSE).

## Contact
For suggestions or inquiries, please reach out:
- [Chetan Jarande Linkedin](https://www.linkedin.com/in/chetan-jarande/)
- [Visit my website](https://chetanjarande-nextjs-portfolio-website.vercel.app)
