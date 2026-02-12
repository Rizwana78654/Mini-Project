<h1 align="center">🏠 HOUSE PRICE PREDICTION SYSTEM</h1>

<p align="center">
Machine Learning Based Web Application for Real Estate Price Estimation<br>
Developed Using Python, OOP & Flask<br><br>

</p>

<hr>

<h2>📑 TABLE OF CONTENTS</h2>

<ol>
<li>Abstract</li>
<li>Introduction</li>
<li>Objectives of the Project</li>
<li>Scope of the Project</li>
<li>Technologies Used</li>
<li>OOP Concepts Used</li>
<li>System Design Using OOP</li>
<li>Workflow of the System</li>
<li>System Architecture and Implementation</li>
<li>Model Training</li>
<li>Model Testing</li>
<li>Flask Web Application</li>
<li>Result and Analysis</li>
<li>Advantages of Using OOP</li>
<li>Applications</li>
<li>Conclusion</li>
</ol>

<hr>

<h2>1️⃣ ABSTRACT</h2>

<p>
The House Price Prediction System is a machine learning-based solution developed 
to estimate the price of residential properties using historical housing data. 
The system analyzes important features such as area, number of bedrooms, 
bathrooms, and location to generate accurate predictions.
</p>

<p>
By applying data preprocessing techniques and training a regression model, 
the system learns relationships between input features and property prices. 
The trained model is integrated into a Flask web application to provide 
real-time predictions through a user-friendly interface.
</p>

<hr>

<h2>2️⃣ INTRODUCTION</h2>

<p>
The real estate industry is rapidly expanding, and property prices vary 
based on multiple dynamic factors. Manual estimation methods often result 
in inconsistent pricing and require expert knowledge.
</p>

<p>
With the advancement of machine learning technologies, predictive systems 
can analyze large datasets efficiently. Automated house price prediction 
reduces human effort and improves consistency in valuation.
</p>

<hr>

<h2>3️⃣ OBJECTIVES OF THE PROJECT</h2>

<ul>
<li>Develop an intelligent and automated house price prediction system.</li>
<li>Perform data preprocessing and feature selection.</li>
<li>Train a reliable machine learning model.</li>
<li>Evaluate model performance using statistical metrics.</li>
<li>Apply OOP concepts for modular system design.</li>
<li>Integrate prediction model with Flask web application.</li>
<li>Provide accurate real-time predictions.</li>
</ul>

<hr>

<h2>4️⃣ SCOPE OF THE PROJECT</h2>


<p>
The system predicts house prices using structured housing datasets. 
It focuses on supervised learning techniques and web deployment.
</p>


<p>
The system does not currently consider real-time economic conditions 
or government policy changes. However, it can be extended with advanced 
algorithms and real-time data integration in future versions.
</p>

<hr>

<h2>5️⃣ TECHNOLOGIES USED</h2>

<ul>
<li><b>Python:</b> Core programming language.</li>
<li><b>Pandas:</b> Data manipulation and preprocessing.</li>
<li><b>NumPy:</b> Numerical computations.</li>
<li><b>Scikit-learn:</b> Linear Regression model implementation.</li>
<li><b>Flask:</b> Backend web framework.</li>
<li><b>HTML & CSS:</b> Frontend user interface.</li>
<li><b>Pickle:</b> Model serialization.</li>
<li><b>GitHub:</b> Version control and collaboration.</li>
</ul>

<hr>

<h2>6️⃣ OOP CONCEPTS USED</h2>

<h3>6.1 Class and Object</h3>
<p>
Classes are blueprints for creating objects. In this project, separate 
classes handle data processing, model training, prediction, and web integration.
</p>


<h2>7️⃣ SYSTEM DESIGN USING OOP</h2>

<h3>7.1 DataHandler Class</h3>
<p>
Responsible for loading datasets, cleaning data, handling missing values, 
encoding categorical features, and scaling numerical features.
</p>

<h3>7.2 ModelTrainer Class</h3>
<p>
Handles splitting data into training and testing sets, training the 
Linear Regression model, evaluating performance, and saving the trained model.
</p>

<h3>7.3 HousePricePredictor Class</h3>
<p>
Loads the trained model and predicts house prices based on user inputs.
</p>

<h3>7.4 WebApp Class</h3>
<p>
Manages Flask routes and connects frontend input forms with backend prediction logic.
</p>

<hr>

<h2>8️⃣ WORKFLOW OF THE SYSTEM</h2>

<ol>
<li>User enters property details in the web form.</li>
<li>Input data is sent to Flask backend.</li>
<li>Data is processed and formatted.</li>
<li>Trained model predicts house price.</li>
<li>Prediction is displayed to the user.</li>
</ol>

<hr>

<h2>9️⃣ SYSTEM ARCHITECTURE AND IMPLEMENTATION</h2>

<h3>9.1 Data Layer</h3>
<p>
Handles data collection, preprocessing, and feature engineering.
</p>

<h3>9.2 Model Layer</h3>
<p>
Implements the machine learning algorithm and evaluates model performance.
</p>

<h3>9.3 Business Logic Layer</h3>
<p>
Processes user input and interacts with the trained model.
</p>

<h3>9.4 Presentation Layer</h3>
<p>
Provides a user-friendly web interface using Flask, HTML, and CSS.
</p>

<hr>

<h2>🔟 MODEL TRAINING</h2>

<h3>10.1 Data Splitting</h3>
<p>
The dataset is divided into training and testing sets (80% - 20%).
</p>

<h3>10.2 Algorithm Selection</h3>
<p>
Linear Regression is chosen to establish relationships between features and prices.
</p>

<h3>10.3 Model Saving</h3>
<p>
After training, the model is saved using Pickle for future use.
</p>

<hr>

<h2>1️⃣1️⃣ MODEL TESTING</h2>

<h3>11.1 Performance Metrics</h3>
<ul>
<li>Mean Squared Error (MSE)</li>
<li>Mean Absolute Error (MAE)</li>
<li>R² Score</li>
</ul>

<h3>11.2 Overfitting Check</h3>
<p>
Testing ensures the model performs well on unseen data.
</p>

<hr>

<h2>1️⃣2️⃣ FLASK WEB APPLICATION</h2>

<h3>12.1 User Interface</h3>
<p>
Users enter house details through an HTML form.
</p>

<h3>12.2 Backend Integration</h3>
<p>
Flask routes handle input and communicate with the ML model.
</p>

<h3>12.3 Real-Time Prediction</h3>
<p>
Predicted price is displayed instantly on the webpage.
</p>

<hr>

<h2>1️⃣3️⃣ RESULT AND ANALYSIS</h2>

<p>
The model achieved strong performance with low error values and 
high R² score. Larger properties and premium locations show higher predicted prices.
</p>

<p>
The results validate the effectiveness of machine learning in 
real estate price estimation.
</p>

<hr>

<h2>1️⃣4️⃣ ADVANTAGES OF USING OOP IN HOUSE PRICE PREDICTION SYSTEM</h2>

<ul>
<li>Organized and structured code.</li>
<li>Easy debugging and maintenance.</li>
<li>Code reusability.</li>
<li>Scalability for future improvements.</li>
<li>Clear separation of responsibilities.</li>
</ul>

<hr>

<h2>1️⃣5️⃣ APPLICATIONS</h2>

<ul>
<li>Real estate price estimation.</li>
<li>Property investment decision-making.</li>
<li>Bank loan valuation systems.</li>
<li>Educational machine learning projects.</li>
<li>Future integration with mobile applications.</li>
</ul>

<hr>

<h2>1️⃣6️⃣ CONCLUSION</h2>

<p>
The House Price Prediction System successfully combines Machine Learning, 
Object-Oriented Programming, and Web Development technologies to create 
an efficient real-world solution.
</p>

<p>
The system provides accurate and reliable house price predictions 
and serves as a foundation for advanced real estate analytics platforms.
</p>

<hr>

<p align="center">
<b>👩‍💻 Project By SHAIK RIZWANA BEGUM</b>
</p>

