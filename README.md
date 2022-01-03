<p align='center'><img height='400' src = 'https://user-images.githubusercontent.com/31500911/147885499-2ebe9f88-b937-4580-8d7d-8b8a405cb857.png'></p>
<br>
<p>Rainfall Prediction is one of the difficult and uncertain tasks that have a significant impact on human society. Timely and accurate forecasting can proactively help reduce human and financial loss. This study presents a set of experiments that involve the use of common machine learning techniques to create models that can predict whether it will rain tomorrow or not based on the weather data for that day</p>
<br>
<h2>What it does </h2>
<p align='center'><img height='400' src = 'https://user-images.githubusercontent.com/31500911/147885585-703ea122-20c5-4463-92df-a1191b72611f.png'></p>
<br>
<h2>Live Demo</h2>
<p align='center'><img height='400' src = ''></p>
<br>
<h2>What has done in model :</h2>
<ul>
  <li>Balancing done for an unbalanced dataset (Over Sampling)</li>
  <li>Label Coding Is Done for Categorical Variables</li>
  <li>Sophisticated imputation like MICE is used</li>
  <li>Outliers can be detected and excluded from the data</li>
  <li>The filter method and wrapper methods are used for feature selection</li>
  <li>Compare speed and performance for different popular models</li>
  <li>Which metric can be the best to judge the performance on an unbalanced data set: precision and F1 score.</li>
</ul>
<br>
<h2>Important Terms</h2>
<h4>Cohen’s Kappa</h4>
<p>Cohen’s kappa statistic is a very good measure that can handle very well both multi-class and imbalanced class problems.</p>
<p>Cohen’s kappa is defined as:</p>
<p>Kappa = (observed accuracy - expected accuracy)/(1 - expected accuracy)</p>
<p>For more details <a href='https://en.wikipedia.org/wiki/Cohen%27s_kappa'>Check</a>
<br>
<h2>Results </h2>
<p align='center'><img height='400' src = 'https://user-images.githubusercontent.com/31500911/147885959-b8c07667-ff41-4e38-8c43-bf7c226e9637.png'></p>
<br>
<p align='center'><img height='400' src = 'https://user-images.githubusercontent.com/31500911/147886098-84e1fc3e-0b85-4a74-812f-5957fcf708b8.png'></p>
<br>
<p align='center'><img height='400' src = 'https://user-images.githubusercontent.com/31500911/147885845-303af9ce-b6a1-477a-b0b1-afa3b171bc04.png'></p>
<br>
<p align='center'><img height='400' src = 'https://user-images.githubusercontent.com/31500911/147885812-f78be2b6-219c-433a-9854-2760225f71cd.png'></p>
<br>
<hr><br>
<p><b>XGBoost</b> and <b>Random Forest</b></b> performed better compared to other models. However, if<b> speed</b> is an important thing to consider, we can stick with <b>Random Forest</b> instead of XGBoost.</p>
