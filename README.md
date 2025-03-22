# 🚀 Blood Cell Detection using Mask R-CNN  

This project applies **Masked R-CNN** for **instance segmentation** on a **Blood Cell dataset**. It detects and segments blood cells in images, producing **bounding boxes, masks, and class labels** for each detected cell.  

## 📌 Features  
✔ Implements **Masked R-CNN** for object detection & segmentation  
✔ Uses a **pretrained COCO model** for feature extraction  
✔ Processes images from a **Blood Cell dataset**  
✔ Visualizes segmented cells with masks & bounding boxes  

## 🛠 Installation  

## 1️⃣ Install Dependencies
```sh
pip install torch torchvision torchaudio
pip install opencv-python numpy matplotlib
pip install git+https://github.com/facebookresearch/detectron2.git
```

## 🎭 Model Training

### 🔹 Preprocessing
- Images are resized and normalized.
- Augmentation techniques like flipping, rotation, and brightness adjustment are applied.

### 🔹 Training
- The model is trained using Masked R-CNN on a labeled dataset.
- Pretrained weights from COCO are used for feature extraction.
- The optimizer and learning rate scheduler are configured for efficient convergence.

### 🔹 Evaluation Metrics
- Precision, recall, and IoU (Intersection over Union) are used to assess performance.
- The model's ability to detect and segment blood cells is analyzed using test images.

## 🖼 Sample Output
```html
<img src="sample_output.png" width="600">
```

## 🏗 Future Improvements
✅ Fine-tune the Masked R-CNN model for higher accuracy  
✅ Train on a custom blood cell dataset  
✅ Deploy as a web-based application  
✅ Optimize inference speed for real-time detection  

## 🤝 Contributing
Pull requests are welcome! Feel free to improve detection accuracy, add features, or optimize the code.

## 📜 License
This project is licensed under the MIT License.



