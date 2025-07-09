📌(EN) – AI-Assisted Meteor Analysis

🌠 Project Overview: 

This project aims to predict the elemental composition of meteors based on their emitted colors during atmospheric entry, using deep learning and image processing techniques. It is structured as a three-stage AI pipeline combining object detection, segmentation, and color-based classification.

🧠 Methodology: 

Object Detection (YOLOv8):
Detects the meteor region in the image.
Segmentation (U-Net with EfficientNet-b4):
Precisely segments the meteor pixels using the segmentation_models_pytorch library.
Color Extraction & Classification:
Extracts dominant RGB values from the segmented region and maps them to probable chemical elements using a custom multi-label classification approach.

📊 Datasets: 

Meteor Dataset: Manually annotated meteor images with bounding boxes and segmentation masks.
Element-Color Dataset: A custom dataset mapping characteristic emission colors to elements, based on scientific literature.

🔧 Technologies Used:

Python, PyTorch, Keras, TensorFlow
OpenCV for image preprocessing
segmentation_models_pytorch, YOLOv8
Matplotlib, Scikit-learn for evaluation and visualization

📈 Evaluation:

Confusion Matrix
ROC Curves
Sample predictions and visual outputs

------------------------------------------------------------------------------------------------------------------------------

📌(TR) – Yapay Zeka Destekli Göktaşı Analizi

🌠 Proje Özeti:

Bu proje, atmosferde yanan göktaşlarının yaydığı renklerden yola çıkarak element bileşimlerini tahmin etmeye yönelik bir yapay zeka sistemidir. Derin öğrenme ve görüntü işleme yöntemleriyle tasarlanmış üç aşamalı bir mimariye sahiptir.

🧠 Yöntem:

Nesne Tespiti (YOLOv8):
Görüntüdeki göktaşı bölgesi belirlenir.
Segmentasyon (U-Net + EfficientNet-b4):
Göktaşı pikselleri segmentation_models_pytorch kütüphanesi ile hassas şekilde ayrıştırılır.
Renk Çıkarımı ve Sınıflandırma:
Segment üzerinden renk bilgisi çıkarılarak çok etiketli sınıflandırma ile element tahmini yapılır.

📊 Veriseti Bilgisi:

Meteor Veriseti: Elle etiketlenmiş göktaşı görüntüleri, maske ve bbox içerir.
Element-Renk Eşleşme Seti: Literatüre dayalı olarak oluşturulan özel renk-element eşlemesi.

🔧 Kullanılan Teknolojiler:

Python, PyTorch, Keras, TensorFlow
OpenCV görüntü işleme için
segmentation_models_pytorch, YOLOv8
Matplotlib, Scikit-learn ile analiz

📈 Değerlendirme:

Confusion Matrix
ROC eğrileri
Örnek çıktı görselleri


📌 Author - Geliştirici

Fatih Özveren
