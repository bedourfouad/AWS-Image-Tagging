# 📸 **Automated Image Tagging System** 🎯

## 🛠️ **Project Overview**  
The **Automated Image Tagging System** is a machine learning project designed to tag images using multi-label classification automatically. Leveraging a subset of the COCO dataset, the system utilizes AWS services for model training, deployment, and real-time image tagging.

## 👥 **Team Members**  
- Ahmed Waheed: Data Engineer 👨‍💻  
- Bedour Fouad: Data Engineer 👩‍💻  
- Menna Osama: Model Development 🧠  
- Norhan El-Sayed: Model Development 🧑‍💻  
- Mina Farid: Deployment & Documentation 🚀

---

## 🌟 **Key Features**  
- **Dataset**: Subset of COCO dataset, optimized for multi-label classification with **80 classes** and **100,000 images** 🖼️.  
- **Model**: Transfer learning using **ResNet50** 🧠.  
- **Training**: Performed on **AWS SageMaker** ⚙️.  
- **Deployment**: Model deployed using **AWS SageMaker Inference Endpoints** and **API Gateway** 🌐.  
- **Application**: A **mobile app** (Flutter) and a **website** were created to showcase real-time image tagging 📱💻.  

---

## 💡 **Problem Solved**  
Manual image tagging is time-consuming and inefficient, especially with the growing volume of visual data. This system automates the process, enabling:  
- 📂 **Better content organization**: Streamlined search and retrieval through accurate image tags.  
- 🌟 **Enhanced user experience**: Personalized recommendations based on tagged images.  
- 💼 **Efficiency**: Reduces manual workload and improves productivity for businesses.  

---

## 📊 **Dataset & Processing**  
- **Classes**: 80 categories relevant to the COCO dataset 📋.  
- **Training Examples**: 100,000 images representing diverse classes 🖼️.  
- **Data Storage**: Stored in **AWS S3** for easy access and integration ☁️.  
- **Preprocessing**: Standardized image sizes, normalization, and augmentation techniques such as flipping and cropping 🖼️🌀.

---

## 🧠 **Model Development & Training**  
We implemented **transfer learning** with **ResNet50** to develop our image classifier. The model was trained using **AWS SageMaker** for scalability and efficiency.  
- 🔄 **Augmentation**: Addressed class imbalance using oversampling and data augmentation techniques.  
- 🧪 **Evaluation**: Achieved a **97.85% accuracy** on the testing set 🎯.

---

## 🚀 **Deployment**  
The model is deployed via **AWS SageMaker** Inference Endpoints.  
- **API Integration**: API Gateway enables interaction with the model through RESTful endpoints 🔗.  
- **Monitoring**: **AWS CloudWatch** logs are used for real-time debugging and monitoring 📈.  

---

## 🌍 **Application/Website Development**  
We built a **mobile app** using **Flutter** and a **website** to demonstrate the model’s capabilities:  
- **API calls** to communicate with the deployed model 🌐.  
- **Image Upload**: Users can upload images for tagging and classification 📸.  
- **Results Displayed**: Predicted labels appear instantly on the interface 🎉.

---

## 🛑 **Challenges**  
Throughout the project, we encountered several obstacles:  
- **Class imbalance**: Handled using targeted augmentation and weighted sampling ⚖️.  
- **Data leakage**: Addressed by modifying the data augmentation process 🚫.  
- **Endpoint bugs**: Resolved by using **AWS CloudWatch** for debugging and performance monitoring 🛠️.

---

## 📦 **Resources & Links**  
- [Demo Website 🌐](http://98.83.114.209/index.html)  
- [Demo App for Android 📱](https://drive.google.com/file/d/1dHICUsV4ggb95AOgsm_Uy9cdsCcY6u9e/view)  
- [Demo App for Windows 💻](https://drive.google.com/file/d/1yvUO-RHiu9qRqP8HLQ6Xcsz2XapMsbKQ/view)  
- [GitHub Repository 💻](https://github.com/MinaFarid1/AWSImageTagging)  
- [Dataset on Kaggle 📊](https://www.kaggle.com/datasets/shubham2703/coco-dataset-for-multi-label-image-classification)

---

## 📚 **Conclusion**  
This project successfully automated multi-label image tagging using transfer learning, AWS infrastructure, and scalable deployment. It streamlines image tagging tasks, saving time and resources while providing businesses with improved organizational tools.

