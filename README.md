Repo for malaria cell classification.   
  
Data source::https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria.

The data consists of 27558 images of blood cells that have been tagged as 'Parasitised' or 'Uninfected' .   
The infected blood cells show a presence of the parasite and which is absent in the uninfected blood cell.  

Model building is done in the following sequence:  
1. Build and test fully connected  neural network model for the classification task.  
2. Build and test CNN models.   
3. In each of the above cases, perform hyper parameter optimization such as selecting the best learning rate , regularisation technique such as dropout layer with the best dropout rate .Select the best model that gives a high recall for paracitised class and also a good accuracy.   
4. Test the select model for different runs of train-test image dataset slices.  
5. Check for the model variance.  

Conclusion:  
It is seen that when blood cell images are read in as a  224x224X3 RGB image , the fully connected neural network models perform very poorly in the classification task.The CNN Models perform fairly well in the feature map generation and hence are able to give a recall of 0.93 for the parasitised class and overall accuracy of 0.95.  
  
Future scope:
1.Can we improve the model metrics by using pretrained models and transfer learning?  
2.Can we get new blood cell images for identification of malarial infection and test the model performance ?  
3.Can you perform a study on how beneficial is this modelling as a tool to aid in malaria diagnosis ?    

    

