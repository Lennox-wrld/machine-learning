A simple fake news detector app

The input is a news headline, the model is classifier that predicts the class of the news segment i.e fake or real

The application can be used for fake news detection in various news sources on the internet. 

The accuracy of the model is 92.7% which is quite impressive. The model can be improved to achieve higher accuracy by increasing the training data. A pre-trained classifier could also be used to make inferences and the accuracy evaluated


To run this app locally, you need to create a directory first and install the requirements.txt file :

mkdir fakenewsdetectorapp
cd fakenewsdetectorapp
pip install -r requirements.txt

Once the dependancies are installed , you can run the cells or change it to a python script and run it as :

python fakedetector.py
