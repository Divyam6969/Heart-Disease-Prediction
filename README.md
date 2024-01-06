
<body>

  <h1>Heart Disease Prediction App</h1>

  <p>Welcome to the Heart Disease Prediction App repository! This application, built using Flask and powered by a Random
    Forest Classification model, aims to provide users with accurate predictions regarding the likelihood of heart disease
    based on various health parameters.</p>
  <p>Dataset for the model is available here https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset</p>

-> Entering data
<br>
<br>
<image  width="600px" src="Screenshots/screenshots.png">
<br>

-> When heart disease not found
<br>
<br>
<image  width="600px" src="Screenshots/screenshots2.png">
<br>

-> When heart disease is found
<br>
<br>
<image  width="600px" src="Screenshots/screenshots3.png">
<br>

  <h2>Features</h2>

  <ul>
    <li><strong>Flask Web Application:</strong> The frontend is developed using Flask, ensuring a user-friendly and
      responsive interface.</li>
    <li><strong>Random Forest Classification Model:</strong> The heart disease prediction model utilizes the Random Forest
      algorithm, offering high accuracy and robustness.</li>
    <li><strong>User-friendly Interface:</strong> Easily input health parameters and receive predictions regarding the
      probability of heart disease.</li>
    <li><strong>Interpretability:</strong> Gain insights into the factors influencing the prediction, enhancing user
      understanding.</li>
  </ul>

  <h2>Usage</h2>

  <ol>
    <li><strong>Clone the Repository:</strong>
      <pre><code>git clone https://github.com/your-username/heart-disease-prediction-app.git
cd heart-disease-prediction-app
</code></pre>
    </li>
    <li><strong>Install Dependencies:</strong>
      <pre><code>pip install -r requirements.txt
</code></pre>
    </li>
    <li><strong>Run the Application:</strong>
      <pre><code>python app.py
</code></pre>
    </li>
    <li><strong>Access the App:</strong> Open your web browser and navigate to <code>http://localhost:5000</code> to use the
      Heart Disease Prediction App.</li>
  </ol>

  <h2>Input Parameters</h2>

  <p>To make predictions, please provide the following health parameters:</p>

 To make predictions, please provide the following health parameters:
<ul>
  <li>Age: Enter your age.</li>
  <li>Sex (0 for female, 1 for male): Specify your gender (0 for female, 1 for male).</li>
  <li>Chest Pain Type (0-3): Indicate the type of chest pain experienced (0-3).</li>
  <li>Resting Blood Pressure: Input your resting blood pressure.</li>
  <li>Serum Cholesterol: Provide your serum cholesterol level.</li>
  <li>Fasting Blood Sugar: Enter your fasting blood sugar level.</li>
  <li>Resting Electrocardiographic Results: Specify resting electrocardiographic results.</li>
  <li>Maximum Heart Rate Achieved: Input the maximum heart rate achieved during exercise.</li>
  <li>Exercise Induced Angina (0 for no, 1 for yes): Indicate if you experience exercise-induced angina (0 for no, 1 for yes).</li>
  <li>ST Depression Induced by Exercise Relative to Rest: Enter the ST depression induced by exercise relative to rest.</li>
  <li>Slope of the Peak Exercise ST Segment: Specify the slope of the peak exercise ST segment.</li>
  <li>Number of Major Vessels Colored by Fluoroscopy (0-3): Indicate the number of major vessels colored by fluoroscopy (0-3).</li>
  <li>Thalassemia: Specify the type of thalassemia.</li>
</ul>
 <h2>License</h2>

  <p>This project is licensed under the <a href="LICENSE">MIT License</a>.</p>

  <p>Thank you for using our Heart Disease Prediction App! Your feedback and contributions are highly appreciated.</p>

  <h2>Contributing</h2>

  <p>We welcome contributions! Feel free to explore the code, enhance the application, or address issues. Create a pull
    request or open an issue to start a discussion.</p>


</body>

