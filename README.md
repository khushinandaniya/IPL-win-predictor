<h1>IPL Win Predictor</h1>
<br>
<p>This project is a machine learning-based web application that predicts the winning probabilities of IPL teams in a live match scenario. The model considers key features such as current score, target, overs, wickets, and venue to provide real-time winning chances.</p>
<br>
<h3>Data Used:</h3>
<ul>
  <li>Matches: match id , season , date, winner etc.</li>
  <li>Deliveries: match id , innings , batting team , bowling team ,overs ,runs etc.</li>
</ul>
<h3>Technologies Used</h3>
<ul>
  <li>Pandas, NumPy – for data wrangling and manipulation</li>
  <li>matplotlib - For visulization</li>
  <li>Scikit-learn – for feature Engineering & Model training </li>
  <li>Pickle - Used to load pre-trained machine learning/data objects</li>
  <li>Streamlit - used to build an interactive web app for predicting IPL match outcomes based on team selections, venue, and match conditions.</li>
</ul>
<h3>Key Features</h3>
<ul>
  <li>Data Loading & Cleaning : 
     <ul>
       <li>Filters and cleans unnecessary columns (like match id, date, umpire data)</li>
       <li>Drops null or irrelevant records (e.g., super overs, abandoned matches).</li>
    </ul>
  </li>
  <li>Feature Engineering : 
    <ul>
      <li>Creates new match-specific features</li>
      <li>Encodes categorical variables (teams, cities) for model training.</li>
    </ul>
  </li>
  <li>Model Building : Trains a Logistic Regression model using scikit-learn.It gives prediction in terms of probability</li>
</ul>
<p>It uses streamlit for interactive user interface. Predicts the win probability for both teams using the trained machine learning model (pipe.pkl).Displays output as percentage chances for each team</p>
<h3>Real World Application</h3>
 <ul>
   <li>Broadcasters & Media Platforms : Star Sports, ESPNcricinfo, Cricbuzz</li>
   <li>Fantasy Sports Platforms : Dream11, MPL, My11Circle</li>
   <li>Sports Gaming</li>
 </ul>
<h1>Summary</h1>
<h4>This model predicts the winning probability of an IPL team during a live match based on the current game situation.</h4>
