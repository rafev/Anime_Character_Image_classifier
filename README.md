# Anime Character Image classifier
Many characters across (and sometimes within) shows have very similar appearances, it can at times be confusing who is who. This is especially true when fan art gets involved, muddying the waters even more! The Jupyter Notebook within this repo contains a proof of concept example that can be used to resolve that with a custom Pytorch Convolution Neural Network (CNN) used to classify anime images from 2 curated datasets originally sourced from the paper [AniWho: A Quick and Accurate Way to Classify Anime Character Faces in Images](https://arxiv.org/pdf/2208.11012v3). This dataset uses four classes, with 50 images each.

Within the notebook is a full walkthrough showing how data was loaded, the model build and layers calculated, training, and performance validation. Additionally, there are visualizations included to assess the dataset, overall model performance, and prediction accuracies.

## Results Overview
The custom CNN was able to achieve an accuracy of 90% on the test set. Example images below show how similar some of the characters are, and further illustrate the performance of the model.
![anime classifier image cropped](https://github.com/user-attachments/assets/40e1ded7-032c-43e3-8db2-ca06a1106522) <br />
### Model performance
The predictive performance of the model is made evident by the exceptionally low training and validation loss, as illustrated below. <br />
![anime classifier loss plot](https://github.com/user-attachments/assets/5497d85b-3ce8-4adc-a249-36b4426dbaab)


