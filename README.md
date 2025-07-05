# Brain-Tumor-Classification-TeachableMachine
Brain tumor classification using MRI images with four categories (No Tumor, Glioma, Meningioma, Pituitary) trained via Teachable Machine and deployed in Python using Anaconda and Visual Studio.

# 🧠 Understanding Brain Tumors
Glioma: A tumor that arises from glial cells in the brain. They can be aggressive and require early detection.

Meningioma: A typically benign tumor that forms on membranes covering the brain and spinal cord.

Pituitary Tumor: Tumors that occur in the pituitary gland, affecting hormone levels.

No Tumor: Normal brain MRI with no tumor present.

MRI imaging is a critical tool in the diagnosis of these conditions. This model helps in automating initial detection to assist radiologists.

# 📊 Dataset Summary
The MRI brain tumor dataset used for training contains a total of 5,712 images, categorized into the following four classes:

| Tumor Type       | Number of Images |
| ---------------- | ---------------- |
| No Tumor         | 1,595            |
| Glioma Tumor     | 1,321            |
| Meningioma Tumor | 1,339            |
| Pituitary Tumor  | 1,457            |

These images were preprocessed and labeled before being used in training via Teachable Machine.

![dataset](https://github.com/user-attachments/assets/973ab780-1aaf-4ad0-adab-0ee59d45a0d0)

The dataset used for training was obtained from Kaggle:
🔗 [Brain Tumor Classification (MRI)](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)


# 🎯 Objective
The goal of this project is to:

- capable model of accurately detecting and classifying different types of brain tumors from MRI images.

- Make it easy to deploy and run the model using Python in a local environment.

- Provide an intuitive way to analyze medical image data with minimal setup.

# 🛠 Tools & Technologies Used
| Tool/Platform         | Description                                                                    |
| --------------------- | ------------------------------------------------------------------------------ |
| **Teachable Machine** | No-code model training platform by Google. Used for image classification.      |
| **Python**            | Core programming language for running the model.                               |
| **Anaconda**          | Environment manager used to install required Python packages and dependencies. |
| **Visual Studio**     | IDE used for writing, running, and debugging Python code.                      |
| **Pillow (PIL)**      | Python Imaging Library for image loading and preprocessing.                    |
| **NumPy**             | Used for numerical operations and image array manipulation.                    |
| **TensorFlow/Keras**  | Framework used to load and run the trained deep learning model.                |
| **Matplotlib**        | Library used for visualizing images and prediction results.                    |

# 🧩 Custom Enhancements
In addition to using the standard exported code from Teachable Machine, I added extra functionality to improve the output experience:

✅ Display the uploaded MRI image

✅ Show the predicted tumor type

✅ Print the prediction confidence 

This enhancement allows for quick visual feedback on the input image and helps in interpreting the model's predictions more clearly.

# 💡 Example Output

Visual Output:

![Screenshot 2025-07-05 145029](https://github.com/user-attachments/assets/b9cc200a-5442-4d71-96d0-24c74c1c2e4c)

Console Output:

![Screenshot 2025-07-05 145042](https://github.com/user-attachments/assets/5a79a3d8-7207-4c67-9fea-30038eb852b7)


