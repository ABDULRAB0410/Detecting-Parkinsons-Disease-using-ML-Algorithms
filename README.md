# Detecting-Parkinsons-Disease-using-ML-Algorithms
This study explores the application of machine learning to distinguish Parkinson's disease from similar clinical presentations, addressing the challenge of early and subtle symptoms. It reviews 209 research studies, revealing promising potential for novel biomarkers and machine learning in improving clinical diagnosis.

INTRODUCTION:-
The global prevalence of Parkinson's disease has surged, reaching 6.1 million in 2016, attributed to aging populations and increased incidence rates. Often, physical symptoms manifest first, like tremors and difficulty walking, preceding cognitive and behavioral issues. Non-motor symptoms, such as attention problems and sleep disturbances, may precede diagnosis. This study explores the role of machine learning in identifying novel diagnostic markers and utilizing alternative measures to detect Parkinson's disease in its early stages or atypical forms.

Machine learning leverages data to generate meaningful representations, making it a valuable tool for Parkinson's disease diagnosis. Various data modalities, including magnetic resonance imaging (MRI) and single-photon emission computed tomography (SPECT), have been analyzed using machine learning models. Recent literature has explored the use of wearable sensors and kinematic data in diagnosis, emphasizing the potential of machine learning techniques in identifying Parkinson's disease.

By synthesizing previous approaches and assessing their suitability, the study contributes to the growing adoption of machine learning algorithms and novel biomarkers in clinical settings, enhancing diagnostic accuracy and informed decision-making in Parkinson's disease diagnosis.

To this dataset we applied 4 algortihms:-
1)Logistic Regression Algorithm 
2)Decision Tree Algorithm 
3)Random Forest Algorithm 
4)K-Nearest Neighbour Algorithm 

Dataset details:-
we distributed data into training and testing. 80% into training and 20% into testing.
Train.shape - (156,22)
Test.shape - (39,22)


1)Logistic Regression Algorithm :-
Here we got Training accuracy (0.8717948717948718)% and Testing accuracy (0.8461538461538461)%.
Confusion matrix is ([5 , 3]
                    [3 , 28]).
So, This is the predicted Training , Testing, confusion matrix accuracies of 
Logistic regression algorithm of Parkinsons disease dataset.

2)Decision Tree Algorithm:-
Here we got Training accuracy (1.0)% and Testing accuracy (0.8717948717948718)%.
Confusion matrix for training data : ([ 40, 0],
                                     [ 0, 116])
Confusion matrix for testing data :([ 6, 2],
                                   [ 3, 28])
So, This is the predicted Training, Testing, and confusion matrix accuracies of 
the Decision Tree algorithm of Parkinson’s disease dataset.

3)Random Forest Algorithm:-
Here we got Training accuracy (1.0)% and Testing accuracy (0.9230769230769231)%.
Confusion matrix for testing data :([ 5, 3],
                                    [ 2, 29])
So, This is the predicted Training, Testing, and confusion matrix accuracies of 
the Random Forest algorithm of the Parkinson’s disease dataset.

4)K-Nearest Neighbour Algorithm:-
Here we got Training accuracy (0.9294871794871795)% and Testing accuracy (0.8205128205128205)%
Confusion matrix for testing data :([ 4, 4],
                                    [ 3, 28])
So, This is the predicted Training, Testing, and confusion matrix accuracies of 
the K-Nearest Neighbour algorithm of the Parkinson’s disease dataset

OBSERVATION and CONCLUSION:-

Voice recordings and handwritten patterns show promise for high patient-level diagnostic accuracy, offering non-invasive data collection. However, there's a gap between model development and clinical application, with limited validation using local participants.
Challenges persist in bridging the gap between machine learning model development and clinical application, warranting further research and validation in real-world settings for Parkinson's disease diagnosis.

Machine learning-assisted diagnosis holds significant promise for systematic clinical decision-making and early-stage Parkinson's disease detection through new biomarkers, offering physicians valuable tools for screening and diagnosis.


