<h3><b>Hey there for everyone!</b></h3>

My name is <b>Vasyukhin Artem</b> and Im glad to see you in my GH repository of <b>"Supervised learning"</b> ML-project!

Today we gonna look at client database of "Beta-bank" for check the reason why people leaving. By the side of view of product manager, catch a new clients is more expensive than save the initial.

Our target - build ML model which can predict will client leave bank or no.

<b>Features (</b>
<p>
<li>RowNumber — row index</li>
<li>CustomerId — unique client ID</li>
<li>Surname</li>
<li>CreditScore</li>
<li>Geography — living country</li>
<li>Gender</li>
<li>Age</li>
<li>Tenure — period of being client</li>
<li>Balance</li>
<li>NumOfProducts — number of products per client</li>
<li>HasCrCard — credit card own</li>
<li>IsActiveMember — activity</li>
<li>EstimatedSalary</li>
</p>

<b>Target</b>
<p>
<li>Exited — факт ухода клиента</li>
</p>

<h3><b>Work plan</b></h3>
<ol>
<li>Import libraries and datasets</li>
<li>EDA</li>
<li>Preparing data for modeling</li>
<li>Modeling</li>
</ol>

<h3><b>RESULTS</b></h3>
<p>
In the course of work we:
<ul>
<li>processed dataset, which applied to construct for construct ML-models;</li>
<li>teached models on the balanced and unbalanced samples;</li>
<li>proved what model, teached on balanced sample, have higher f-score than unbalanced;</li>
<li>created graphic of ROC-curve and calculate AUC-score. </li>
</ul>
</p>

<p>
Total result of ROC-curve prooves what balanced upscaled model of Random Forest is better than balanced model without scaling: 0.864 against 0.854.
</p

