# Infamous Films

This is a hollywood movie recommendation system built with Python. I have used IMDB 5000 Movie Dataset to built this.
Link to dataset :- https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset

Link to the web application :- https://movie-recommend-nandini.herokuapp.com/

I have used Flask framework to built web app.

<hr>

# Files:
*In the preprocessing.ipynb file the Data Preprocessing part has been done.

*requirements.txt-Contains all the libraries required for the model creation.

*The application is run from the main.py file.

<hr>
<h1>Methodology:</h1>
<p>I implemented the system using machine learning and cluster analysis based on a hybrid recommendation approach. The system takes in the users’ personal information and predicts their movie preferences using well-trained support vector machine (SVM) models. Based on the SVM prediction it selects movies from the dataset, clusters the movies and generates questions to the users. Based on the users’ answers, it refines its movie set and it finally recommends movies for the users. In the process we traverse the parameter space, thus enabling the customizability of the system.</p>
  <img src = "https://firebasestorage.googleapis.com/v0/b/bikengo-b86b3.appspot.com/o/1.jpeg?alt=media&token=e730f203-39d8-4ed2-bdb6-ddb534c107c2">
<hr>
<h1>Screenshots: </h1>
<h2>Home Screen</h2>
<p>This is the first screen you see when you open the link</p>
<img src ="https://firebasestorage.googleapis.com/v0/b/bikengo-b86b3.appspot.com/o/2.jpeg?alt=media&token=ba3bf33f-8c70-49f8-ab08-ba1e7901b32c">
<h2>Incorrect Movie name entered</h2>
<p>I have added over 5000 Hollywood movie dataset. However, if the user enters any other name, or the spelling is incorrect, the app will show an error.</p>
<img src ="https://firebasestorage.googleapis.com/v0/b/bikengo-b86b3.appspot.com/o/3.jpeg?alt=media&token=df3aa448-8e7b-421c-bf8c-c7e4ac44c094">
<h2>Recommendations</h2>
<p>Here you can see the list of recommended movies, if the user entered "Despicable me". All the movies from our data set, that are similar to it will appear below.</p>
<img src = "https://firebasestorage.googleapis.com/v0/b/bikengo-b86b3.appspot.com/o/4.jpeg?alt=media&token=93c21887-1d5a-4f61-852c-51ca0d8e0c8b">

<hr>



