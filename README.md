Data from https://github.com/DomSamangy/NBA_Shots_04_24
# **Stephen Curry Shot Predictor**
Predicts whether Stephen Curry will make a shot or not based on input (eg. time remaining, shot angle, shot distance etc.)

# **Data**
The data was taken from DomSamangy's repository and altered to produce a csv file with every Stephen Curry shot. Curry's rookie and sophomore seasons in the league were removed from the dataset for more accurate models.

# **Implementation** 
The accuracy of the best model, which was Gradient Boosting, was 64.5% which outperforms most NBA shot prediction models available on the internet. Different methods including Neural Networks, Random Forest, and SVM were tested with some producing similar results (~64%) 
The confusion matrix showed that 

# **Confusion Matrix of Gradient Boosting Model**
![confusion_matrix](https://github.com/alityb/Stephen-Curry-Shot-Predictor/assets/161126071/52c06475-5746-4c7b-87df-1408de06e26e)

# **Recommendations** 
Accuracy could rise when considering different features. Adding different features to the dataset would be helpful, such as the proximity of the defender in each shot. 
