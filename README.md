# MedRecSys
Medical Recommender System for image classification without retraining

![image](https://github.com/user-attachments/assets/66c386ee-cf30-44da-9fb2-110fcd0a579d)

# Classification Task

**Traditional ML**

- Support Vector Machine (SVM)
- Decision Tree (DT)
- Random Forest (RF)
- XGBoost

**Deep leaning**

- CNN
- LSTM and GRU
- Capsule Net
- Transfer learning (ResNet, DenseNet, VGG16,...)
- Transformer
- Swin Transformer

# phases

**Create MedicalRec dataset**

Ref | #Sample| #Train | #Test | #Validation | K-fold | Width | hight | #channel | #Class | Domain | Accu| Pre| Rec| F1| AUC| Model
--- | --- | --- | --- |--- |--- |--- |--- |--- |--- |--- |---|---|---|---|---|---
[1] | 10000 | 7000 | 20000 |10000 | Yes | 255 | 255 | 3 | 2 | Tumor Classification | 0.91| 0.90| 0.93| 0.92| 0.92| SVM


**Write dataset report**


![photo_2025-09-25_16-23-11](https://github.com/user-attachments/assets/72152c26-fd9e-49e3-b448-d547fd132b9f)

**Train Transformer recommander model**


![photo_2025-09-25_16-23-12](https://github.com/user-attachments/assets/108b48ba-8693-4c6f-ba8d-d17b0e2fcf78)


**Testing in real data**


**Save weights and public code**
# MedRecSys

## Project Description
Medical Recommender System for image classification without retraining. This project introduces a zero-shot learning framework that eliminates the need for retraining on new datasets, reducing computational costs and accelerating clinical deployment.

## Key Features
- Zero-shot learning for medical image classification
- Adaptive framework for new categories
- Open-source codebase

## Research Paper
This work is currently under review at **IEEE Transactions on Pattern Analysis and Machine Intelligence**.

- Preprint: [Link to arXiv](https://arxiv.org/abs/2606.07553)
- GitHub Repository: [Link](https://github.com/aysahasanzade/MedRecSys)

## Author
**Aysa Hasanzade Bashkandi**
- [Google Scholar](https://scholar.google.com/citations?user=5wW7R3UAAAAJ&hl=en)
- [GitHub](https://github.com/aysahasanzade)
- [ORCID](https://orcid.org/0009-0001-0413-3367)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
This project was developed through independent research collaboration with Toronto Metropolitan University.











COLLABORATION WITH:[ MedicalRec](https://github.com/Ramin1Mousa/MedicalRec/tree/main)
