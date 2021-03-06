# cover_type_classification
### Objective: Build a deep learning model to predict the forest cover type from different cartographic variables. 
### Given:    
1. Cover Types: ['Spruce/Fir', 'Lodgepole Pine','Ponderosa Pine', 'Cottonwood/Willow','Aspen', 'Douglas-fir', 'Krummholz']    
2. A csv file ('cover_data.csv') that contains 581012 observations. Each observation has 55 columns (54 features and the last one being the class). 

### Assumption(s):    
1. There are no separate test dataset. So, one must hold-out a small percentage of given input as test data.    
2. There is no information about the use of predictions. Hence, we do not know how what to focus on (precision or recall). Generally, it's a good idea to have both scores 'high'. 

### Expected output:    
1. A good model.    
2. Model performance over epochs (accuracy, loss plots)    
3. Some classification metrics (heatmap of confusion-matrix, classification-report etc).    
4. Conclusions, thoughts and ways to improve classification accuracy.
