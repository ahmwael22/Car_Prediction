<!DOCTYPE html>
<html lang="en">
<head>

<h1>Steps</h1>

<!-- Create a list of points -->
<ul class="point-list">
  <li><a href="#Importing libraries">Importing libraries</a></li>
  <li><a href="#Read_data">Read_data</a></li>
  <li><a href="#Data_Exoplaration">Data_Exoplaration</a></li>
    <li><a href="#Data_cleaning And preprocessing">Data_cleaning And preprocessing</a></li>
    <li><a href="# Data_Visualization">Data_Visualization</a></li>
     <li><a href="#Model_Traning">Model_Traning</a></li>

</ul>

<!-- Descriptions for each point -->
<div id="Importing libraries">
  <h2>Importing libraries</h2>
  <p>Here i used libraries like numpy for arithmatics used , pandas for reading files and other uses, matplotlib for plotting 
 , seaborn for visualization the data  and function like trani test split to seperate data for preparing modiling </p>
</div>

<div id="Read_data">
  <h2>Read_data</h2>
  <p>Iam reading the dataset form my PC</p>
</div>

<div id="Data_Exoplaration">
  <h2>Data_Exoplaration</h2>
  <p>here i'am trying to understand the data and generate the maximum information from it by get the info () and the description of the mathimatical data and find outliers and find null values and the quantiles of the data and calculate the distinct values of specific columns .</p>
</div>
<div id="Data_cleaning And preprocessing">
  <h2>Data_Exoplaration</h2>
  <p>here i found unpured columns like "mileage" ,"engine" and "max_power" that have symbol make it not integer i make a function the deal with that and make them pure , then  i droped the unuseful columns like "name" , "seller_type," torque " and "owner" then i make transforming categorical variables into numerical representations ( feature encoding ) .</p>
</div>
<div id=" Data_Visualization">
  <h2> Data_Visualization </h2>
  <p>here i make a fuction that generate relation plot of kind scatter plot that give us the intuition of the relation between "selling_price" and other columns .</p>
</div>
<div id="Model_Traning">
  <h2>Model_Traning </h2>
  <p>here i chosse LinerRegression () model to predict the future input and but when i found that the accuracy of the model is not satisfied because the outliers of "selling_price" i replace the input with log("selling_price") then drop selling_price column .</p>
</div>



</body>
</html>
