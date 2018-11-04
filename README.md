# Dog-Breeds-Image-Classifier
This project is part of [Udacity](https://www.udacity.com "Udacity - Be in demand")'s [AI Programming with Python Nanodegree](https://www.udacity.com/course/ai-programming-python-nanodegree--nd089).

The goals of this project is to improve Python skills and to determine how well the "best" 
classification algorithm works on correctly identifying a dog's breed.

## Versions
- [Anaconda 5.3 with Python 3](https://www.anaconda.com/download/)

### VGG results:
Number of Images         :  40  
Number of Dog Images     :  30  
Number of Non-Dog Images :  10  
% Correct Dogs           : 1.00  
% Correct "Not-a" Dog    : 1.00  
% Correct Breed          : 0.93  
% Match                  : 0.88  

Misclassified Breed's of Dog:  
Pet image:       great pyrenees, Classifier label:                         kuvasz  
Pet image:               beagle, Classifier label:  walker hound, walker foxhound  

Total Elapsed Runtime: 0:0:51

### RESNET results:
Number of Images         :  40  
Number of Dog Images     :  30  
Number of Non-Dog Images :  10  
% Correct Dogs           : 1.00  
% Correct "Not-a" Dog    : 0.90  
% Correct Breed          : 0.90  
% Match                  : 0.82  

Misclassified Dogs:  
Pet image:                  cat, Classifier label: norwegian elkhound, elkhound  

Misclassified Breed's of Dog:  
Pet image:       great pyrenees, Classifier label:                         kuvasz  
Pet image:               beagle, Classifier label:  walker hound, walker foxhound  
Pet image:     golden retriever, Classifier label:                       leonberg  

Total Elapsed Runtime: 0:0:7

### ALEXNET results:
Number of Images         :  40  
Number of Dog Images     :  30  
Number of Non-Dog Images :  10  
% Correct Dogs           : 1.00  
% Correct "Not-a" Dog    : 1.00  
% Correct Breed          : 0.80  
% Match                  : 0.75  

Misclassified Breed's of Dog:  
Pet image:       great pyrenees, Classifier label:                         kuvasz  
Pet image:               beagle, Classifier label:  walker hound, walker foxhound  
Pet image:       boston terrier, Classifier label:                        basenji  
Pet image:               beagle, Classifier label:               english foxhound  
Pet image:     golden retriever, Classifier label:           afghan hound, afghan  
Pet image:     golden retriever, Classifier label:                tibetan mastiff  

Total Elapsed Runtime: 0:0:3

The results are also presented in files vgg_uploaded-images.txt, resnet_uploaded-images.txt, alexnet_uploaded-images.txt.  
The results of 4 images test are presendted in uploaded_images/my_classify_uploaded_images_results.txt.  

According to the received results the best model architecture is VGG. VGG classified the provided dog images 
and uploaded images better since the results of classification were closer to the actual breeds
and classification results of dog and non-dog images were done with 100% accuracy.
