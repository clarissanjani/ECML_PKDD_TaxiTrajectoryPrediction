# Advanced Seminar Operations & Supply Chain Management (WIB22964): Logistics and Supply Chain Management
 ==============================
 ECML_PKDD_TaxiTrajectoryPrediction
As part of the Advanced Seminar Class at the Technical University of Munich, I wrote a seminar paper and performed data analysis on a former Kaggle competition on prediction taxi trajectories. 

https://www.kaggle.com/competitions/pkdd-15-predict-taxi-service-trajectory-i/overview

 ## Project Details
 **Description**: This paper will leverage the ECML/PKDD 15 Taxi Trajectory Prediction dataset which consists of initial partial trajectories of taxi rides in Porto, Portugal. The dataset will be enriched with data from Location-Based Social Networks (LBSNs) like FourSquare that can provide the number and type of activities in an area based on predefined categories. The study compares various unsupervised learning model approaches that work with and without the point of interests data to determine whether or not adding data on hotspots is valuable in prediction taxi next destinations.  
 ## Environment
The project was developed with Python 3.9. We used Pycharm as our IDE as well as used JupyterLab to run our notebooks. It is possible to run the notebooks also on Jupyter Notebook. We also create a scenario in Vadere as part of the bonus question in Task 4. 
 ## How to test the software
Each task has its own separate folder structure with the relevant JupyterLab / Jupyter Notebook and python scripts. 
 ------------

     ├── README.md                        
     ├── Task 1
     │   ├── Task 1 Part 1.ipynb    
     │   ├── Task 1 Part 2.ipynb   
     │   ├── Task 1 Part 3.ipynb    
     │   ├── utils.py
     │   └── data 
     │     ├── pcadataset.txt 
     │     └── data_DMAP_PCA_vadere.txt
     │
     ├── Task 2    
     │   ├── diffusion_map.py   
     │   └── diffusion_maps.ipynb  
     │
     ├── Task 3                
     │   └── Task3.ipynb    
     │
     └── Task 4
         ├── Task4.ipynb         
         ├── Task4_Bonus.scenario       
         └── data   
           ├── FireEvac_test_set.npy 
           └── FireEvac_train_set.npy


 ## Credits and References
 Keras. (2020). Keras documentation: Variational Autoencoder. Keras. Retrieved June 22, 2022, from https://keras.io/examples/generative/vae/ 

