# BERT-for-multiclassification
The project is about predicting the basetags ie presale, postsale or others for a chat of the customer and then predict subtags which has more than 50 subcategories.
Here I have uploaded some training files and pipeline.
I have trained model on local machine without GPU and also on GPU server separately(which I havent uploaded).
You should create small modules so that you can call them in pipelines. I have put all functions in pipeline itself so that when you run the code it should work.
I deployment file, I used load_data() as I am loading the file from mongodb. Here, you can provide your own test dataset.
I am not providing any dataset here as its company's data. You can use any text data you want to classify. 
I have also written some keyword extraction codes in sales_class.ipynb using KeyBert which you can skip.
For requirement file, there is no specific requirement. Just pip install whatever module you dont have. All versions are latest.
