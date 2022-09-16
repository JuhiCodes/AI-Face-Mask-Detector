Directory Structure and description of content:

DATASET —-> (Training and Testing Categories images are taken from this dataset)

Train_Data —-> no_mask ( not wearing mask )
	     —-> ffp2_mask (N95 mask )
	     —-> cloth_mask (cloth type of mask )
	     —-> surgical_mask ( surgical mask )
	     —-> N95_with_valve ( N95 with a valve mask )

Testing_Categories -> gender - male , female
		  -> age - children, young, old
			

Face_mask_detector_AI.ipynb —-> Colab notebook for the code

modelCNN.pkl —-> Convolutional Neural Network model

Classification_Report —-> Documentation for the project

Expectations-of-Originality —> originality signed by all team members.

Steps to run the project—>

1) Open Face_mask_detector_AI.ipynb file
2) Uncompress the dataset zip file and upload the given dataset on google drive
3) If you want to use the trained model, upload the model in contents folder of google collar.
4) Run all the cells.

NOTE : There is a pyTorch bug which might cause problem while loading the model, due to which it is advisable to re train the model every time a notebook is restarted.

		
