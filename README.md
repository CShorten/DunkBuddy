# DunkBuddy
<h5> Get the Peak Height from a Dunk video </h5>
<h3> Project Motivation </h3>


<h1> Data Collection and Annotation</h1>
<h2> Collection and Annotation Pipeline </h2>
<ul>
  <li> Extract frames from each dunk clip ~ 2 minutes long </li>
  <li> Use image classifier to filter clips without a dunker in them </li>
  <li> Label peak height jump </li>
</ul>

<h2> Self-Supervised Learning from Peak Height Label </h2>

<h1> Model Training </h1>
<h2> Image Classifier Training </h2>
The first image classifier will detect if a person is in the frame or not, the second classifier will tell if the person has jumped yet.
The purpose of these classifiers is to filter the raw data and make it easier to assemble a dataset for the max height classifier.

<h2> Training a Siamese Neural Network </h2>

<h1> Hyperparameter Optimization </h1>

<h1> Performance Analysis </h1>
