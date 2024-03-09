# Hypoglycemia_Classification_T1D_T2Prediabetes
This work classifies the time before the onset of hypoglycemia on patients with type 1 diabetes (T1D) and tested on people with type 2 pre-diabetes (T2PD) as well as trained on T2DP and tested on T1D with the same 1DCNN model.<br>
The utilized datasets are:
- The D1NAMO dataset (T1D)
- The Big Ideas Lab dataset (BILab) (T2PD) <br>


The utilized classes are:
- the hypoglycemic event (class 0)
- 15 minutes before hypoglycemia (class 1)
- less than 30 minutes before hypoglycemia  (class 2)
- less than 1 hour before hypoglycemia (class 3)
- less than 2 hours before hypoglycemia (class 4)
- less than 3 hours before hypoglycemia (class 5)
- more than 6 hours before hypoglycemia (class 6).

The jupyter notebook "1DCNN_Model" contains the functions for the 1DCNN model initialization and running 
- the model is once trained with 7 classes and once with 5 classes
- the model is traiend on both datasets and transfer learning is tested with the other dataset
- different thresholds for defining hypoglycemia are compared for the data of T2PD
- the trained models are saved in the "Models" folder
- the confusion matrices are saved in the "Confusion_Matrices" folder
