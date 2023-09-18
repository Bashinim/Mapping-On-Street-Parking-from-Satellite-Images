Parking Space Detection
=========================

This project contains the workings of the parking lots detection research.

Project Organization
------------


	├── README.md             					<- The top-level README of this project.
	│
	├── Mask_RCNN_FPN			  				<- This folder contains the jupyter notebooks used for running the model on the datasets.
	│
	├── Image_and_annotation_processing         <- This folder contains the jupyter notebooks used for splitting larger image tiles
	│												to small image tiles, data augmentation steps and post processing steps.
	├── Post_processing							<- This folder contains the jupyter notebooks used for post processing steps such as 
	│												removing the false positive predictions and creating the parking space maps.
	├── Calculating_the_matrics				<- This folder contains the jupyter notebooks used for canculating the evaluation matrics as well as geojson files used for 
	|												as geojson files used for calculating them.
	├── Link to annotations                     <- The shared link(https://drive.google.com/drive/folders/1PzQkBffiDv-0VsA-FSUH7XUh4Vzbeoxg?usp=sharing) contains the annotations of 
	|												Berlin 2020 DOP dataset for a selected geographical area.
--------
