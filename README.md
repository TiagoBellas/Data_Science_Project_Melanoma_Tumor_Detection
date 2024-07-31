# Data_Science_Project_Melanoma_Tumor_Detection


<div style="color:white;display:fill;border-radius:8px;
            background-color:#03112A;font-size:150%;
            letter-spacing:1.0px;background-image: url(https://i.imgur.com/GVd0La1.png)">
    <p style="padding: 8px;color:white;"><b><b><span style='color:#e61227'></span></b> Problem Statement</b></p>
</div>

The accurate detection and classification of **melanoma** play a crucial role in the diagnosis and treatment planning of patients. However, manual interpretation of medical images, such as dermoscopic scans, can be time-consuming and subjective, leading to potential errors and delays in patient care. Therefore, there is a need for an automated and reliable method to detect and classify melanoma from medical images.

<div style="color:white;display:fill;border-radius:8px;
            background-color:#03112A;font-size:150%;
            letter-spacing:1.0px;background-image: url(https://i.imgur.com/GVd0La1.png)">
    <p style="padding: 8px;color:white;"><b><b><span style='color:#e61227'></span></b> Study Aim</b></p>
</div>

This study aims to develop a Convolutional Neural Network **(CNN)** using the **Keras** framework that can accurately detect and classify **Melanoma Tumors** from many curated images where every pixel holds the potential to redefine early detection. The CNN will be trained on a large dataset (13900 images) to learn the patterns and features associated with different skin types and also the views of melanoma's diverse manifestations.The study aims develop reliable models with high accuracy for melanoma classification.

![image](https://github.com/user-attachments/assets/1c2e1d60-6c96-43c3-8c0f-7e34ec843847)




<h2> NOTE: Skip this if running locally! </h2>

<div style="color:white;display:fill;border-radius:8px;
            background-color:#03112A;font-size:150%;
            letter-spacing:1.0px;background-image: url(https://i.imgur.com/GVd0La1.png)">
    <p style="padding: 8px;color:white;"><b><b><span style='color:#e61227'></span></b> Preparing the enviroment using Google Colab GPU</b></p>
</div>

As train enviroment we decide to move forward using the Google Colab GPU (free version) once the power of computational using GPUs is very efficient became the training process more fast (200x) than locally train. With this configuration we can train and also test many hipermarameters to increse the model performance.

To be able to get access to Google Colab GPUs we needed:

1. Change the RunTime at the top menu setting: 'Runtime -> Change Runtime Type --> under the Hardware Accelerator
2. Download the repository to config the GPUs for ML
3. Install the python lib colab


