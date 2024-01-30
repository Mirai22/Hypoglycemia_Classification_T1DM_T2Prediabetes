# Hypoglycemia_Classification_T1DM_T2Prediabetes
The time before the onset of hypoglycemia is classified on T1DM patients and tested on t2DM pre-diabetics as well as trained on T2DM pre-diabetics and tested on T1DM diabetics with the same 1DCNN model

- the jupyter notebook 1DCNN_Model contains the functions for the model initialization and running 
- the model runs on the D1NAMO and BigLab patients and transfer learning is tested with the other dataset
- threshold 70, 75, 80, and 85 are tested for the BigLab (pre-diabetes) dataset 

- the trained models are saved in Models/
- and the consufion matrices are saved in Confusion_Matrices/
