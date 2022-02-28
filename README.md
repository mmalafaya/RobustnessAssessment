# RobustnessAssessment
Implementation of post-hoc XAI methods to assess the coherence of a CNN lung malignancy classifier over different training sets.

The post-hoc models are implemented in a pre-trained CNN that predicts lung nodule malignancy. Four post-hoc XAI models are studied: Saliency Maps, Integrated Gradients, LRP and DeepLIFT. Visual Explanations are generated for the test set of 10 different versions of the networks trained with differente train-test splits. Four different resolutions are applied for each method explanations, and similarity metrics are applied to compare the resemblance of explanation masks for a single prediction for several versions of the model.

The expected results are the following:

<img width="472" alt="m16" src="https://user-images.githubusercontent.com/100602009/156016160-6b611929-6e36-40b6-adf9-befe244d8697.png">

This code is built using the publicly LIDC-IDRI Dataset for lung cancer screening.
