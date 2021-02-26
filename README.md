# Classification

### simpsons_classification_github.ipynb
1. The project is based on a home task of the MIPT online course (https://stepik.org/lesson/345648/step/1?unit=329389, Rusian language).
2. Pre-trained ResNet50 has been used and finetuned. The model showed a mean F-score >98% on inference on the Kaggle leaderboard.
3. The notebook was not written from scratch: data preprocessing and preparation (dataloader etc.) were and provided in the home task. 
4. The goal of this task was achievement F-score > 83% (1 point) and >97% (15 points).

### Melanoma_pet_project.ipynb
1. It was my self-project. The idea arose from the desire to check my two lesions (brown dots) on my right-hand.
2. The corresponding dataset was found on Kaggle: https://www.kaggle.com/wanderdust/skin-lesion-analysis-toward-melanoma-detection. 
3. Finetuned Resnet152 model has been used for classification problems.
4. There was an imbalance of classes was detected in the dataset therefore Focal Loss has been used to avoiding class imbalance problems and getting better training results.
5. The notebook finished with two photos of my right-hand lesions and they were detected as benign - not malignant, as it was expected. 
6. Link to trained model from my google drive: https://drive.google.com/file/d/1-9BYpg4YkKXhMzGln_LMQpChbwFgL45w/view?usp=sharing
