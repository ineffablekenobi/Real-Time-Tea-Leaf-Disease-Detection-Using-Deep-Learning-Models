# Real-Time Tea Leaf Disease Detection Using Deep Learning Models

<div align="center">
  
## Tea Leaf Detection

</div>

## 📑 Abstract

Tea leaf diseases pose a significant threat to crop productivity, highlighting the need for efficient and accurate detection methods. The lack of cost-effective, lightweight models for deployment on end devices limits real-time detection. This study addressed this by annotating and utilizing the previously unlabeled **Tea Sickness Dataset** for object detection and deploying fine-tuned models on mobile devices.

The **YOLO-NAS-s**, **YOLOv8n**, **YOLOv5nu**, and **SSD-MobileNetV2** models were fine-tuned using this dataset to detect diseased tea leaves, achieving state-of-the-art performance. Among them, **YOLOv5nu** achieved a maximum mAP@50 of **0.969** and an F1-score of **0.927**, demonstrating exceptional accuracy. Its lightweight architecture ensures fast inference and low resource usage, offering a balance between performance and computational efficiency, making it well-suited for real-time deployment.

After the models were evaluated, the two most lightweight models were deployed on mobile devices, demonstrating the feasibility of using high-performance and lightweight models for real-time plant disease monitoring.

## 🌟 Key Features

- Annotation of previously unlabeled Tea Sickness Dataset
- Fine-tuning of multiple state-of-the-art object detection models
- Performance evaluation with metrics including mAP@50 and F1-score
- Deployment of lightweight models on mobile devices
- Real-time inference capabilities for practical field applications


## 📱 Mobile Deployment

The two most lightweight models were successfully deployed on mobile devices, enabling:

- Real-time disease detection in the field
- User-friendly interface for farmers and agricultural experts
- Minimal resource consumption
- Offline operation capability


## 📚 Citation

```bibtex
@article{sarker2024tea,
  author = {Sarker, Swapnil Sharma and Islam, Ashiqul and Talukder Raktim, Raufun and Roshni, Sanjana and Joy, Sajib Kumar Saha and Shah, Faisal},
  title = {Real-Time Tea Leaf Disease Detection Using Deep Learning-Based Models},
  journal = {Journal Name or Preprint Platform},
  year = {2024},
  month = {November},
  doi = {10.13140/RG.2.2.10031.24483}
}
```

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
