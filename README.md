<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  
</head>
<body>

<h1>🍽️ Zomato Restaurants Data Analysis & Prediction</h1>

<blockquote>
  <strong>"Turning restaurant data into real-world business intelligence with Machine Learning."</strong>
</blockquote>

<hr>

<h2>📌 Project Objective</h2>
<p>
This project aims to perform a <strong>deep analysis</strong> of Zomato restaurant data and build a <strong>Machine Learning model</strong> to:
<ul>
  <li>Analyze restaurant trends (location, cost, ratings, cuisines).</li>
  <li>Predict restaurant ratings based on features like cuisine type, location, price range, and services offered.</li>
</ul>
The goal is to create <strong>actionable insights</strong> for restaurant owners, marketers, and investors, and to showcase <strong>predictive modeling</strong> capabilities.
</p>

<hr>

<h2>🛠️ Technologies and Libraries</h2>
<table border="1" cellpadding="5" cellspacing="0">
<thead>
<tr>
<th>Tool</th>
<th>Purpose</th>
</tr>
</thead>
<tbody>
<tr><td>Python</td><td>Core programming</td></tr>
<tr><td>Pandas</td><td>Data manipulation</td></tr>
<tr><td>NumPy</td><td>Numerical computations</td></tr>
<tr><td>Matplotlib & Seaborn</td><td>Data visualization</td></tr>
<tr><td>Plotly</td><td>Interactive plots</td></tr>
<tr><td>Scikit-learn</td><td>Machine Learning (model building, evaluation)</td></tr>
<tr><td>Jupyter Notebook</td><td>Development environment</td></tr>
</tbody>
</table>

<hr>

<h2>📊 Key Data Analysis Insights</h2>
<ul>
  <li><strong>City Analysis:</strong> Identified cities with the highest restaurant density.</li>
  <li><strong>Cuisine Preferences:</strong> Highlighted the most loved cuisines across cities.</li>
  <li><strong>Cost vs Rating Relationship:</strong> Found how restaurant cost affects customer ratings.</li>
  <li><strong>Service Feature Impact:</strong> Analyzed the effect of online ordering and table booking options.</li>
</ul>

<hr>

<h2>🤖 Machine Learning Component</h2>
<p><strong>Problem Statement:</strong> Predict whether a restaurant will have a high rating based on its features.</p>

<p><strong>Approach:</strong></p>
<ul>
  <li>Labeled high/low rated restaurants (based on a rating threshold).</li>
  <li>Feature Engineering: Extracted meaningful features from raw data.</li>
  <li>Successfully built a <strong>Random Forest</strong> model to predict "Highly Rated" restaurants.</li>
  <li>Feature engineering on 'Price' and 'Votes' played a key role in improving model performance.</li>
  <li><strong>ROC Curve analysis</strong> shows promising classification ability.</li>
</ul>

<hr>

<h2>⚙️ How to Set Up Locally</h2>

<h3>1. Clone the repository</h3>
<pre><code class="language-bash">
git clone https://github.com/yourusername/zomato-analysis.git
cd zomato-analysis
</code></pre>

<h3>2. Install required dependencies</h3>
<pre><code class="language-bash">
pip install -r requirements.txt
</code></pre>

<h3>3. Or manually install required libraries</h3>
<pre><code class="language-bash">
pip install pandas numpy matplotlib seaborn plotly scikit-learn
</code></pre>

<h3>4. Launch the Jupyter Notebook</h3>
<pre><code class="language-bash">
jupyter notebook Zomato_Analysis.ipynb
</code></pre>

<hr>

<h2>📜 License</h2>
<p>Distributed under the <strong>MIT License</strong>. Feel free to use and modify!</p>

</body>
</html>
