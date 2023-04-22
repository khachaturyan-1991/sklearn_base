# sklearn_base
Implementation of basic sci-kit learn models like linear/logistic regration, Random Forest, SVM and others on variouse datasets.

Folders:

 - BinaryLogistic containes analyses of data where target should be classified into two categories:
    * titanic dataset where the model has to predict chances of a passengaer with given featuers would have survived or not
    * click on Add where a model has to predict chances of an Ad button should clicked
 The follwoing libraries are implemented and compared:
    * Logistic regrassion
    * RandomForest
    * SVM with different kernels Poly, RBG, Sigmoid
To improve the results follwoing methods were used:
    * data scaling to bring all features values to comparable scales
    * ROC curve
    * Hyperparameters optimization
Eventually entire possedure is wrapped up into a Pipeline

- LinearModels where contitnouse target values should be predicted:
    * BikeRentDataset where number of retn bikes should be predicted based on feature data like day time, wheather etc.
The following librareis are implemented and compares:
    * Linear regrassion
    * RandomForest
To improve the results follwing methods were used:
    * Polynomial feature expansion
    * Hyperparameter optimizaiton
Eventually a customized pipeline was build





