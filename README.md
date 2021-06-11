<h1>Amazon Vine Analysis</h1>

<h2>Overview</h2>

<h3>Purpose</h3>
<p>
  The purpose of this project is to determine whether or not reviews resulting from the Amazon Vince program contain positivity bias.  This review was conducted on available Amazon Review data for video games using PySpark.
</p>


<h2>Results</h2>

<h3>Vine and Non-Vine Reviews</h3>
<p align='center'>
  <img src='https://github.com/tc9993/amazon-vine-analysis/blob/main/Resources/paid_stats.PNG?raw=true' alt='Amazon Paid Reviews'><br>
  <b>Figure 1.1: </b>Amazon Paid Reviews
</p>

<p align='center'>
  <img src='https://github.com/tc9993/amazon-vine-analysis/blob/main/Resources/unpaid_stats.PNG?raw=true' alt='Amazon Unpaid Reviews'><br>
  <b>Figure 1.2: </b>Amazon Unpaid Reviews
</p>

<ul>
  <li>How many Vine reviews and non-Vine reviews were there?
  <ul>
  <li><b>Vine: </b>94</li>
  <li><b>Non-Vine: </b>40,471</li>
  </ul>
  </li>
  
  <li>How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  <ul>
  <li><b>Vine: </b>48</li>
  <li><b>Non-Vine: </b>15,663</li>
  </ul>
  </li> 
  
  <li>What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  <ul>
  <li><b>Vine: </b>51%</li>
  <li><b>Non-Vine: </b>39%</li>
  </ul>
  </li> 

<h2>Summary</h2>

<h3>Positivity Bias</h3>
<p>
  After reviewing and categorizing the available data on video game reviews, it appears that there <b>is</b> positivity bias from Amazon Vine paid reviews.  When looking at the population of paid reviews, 51% were 5-Star reviews, the highest review score available.  This is considerably higher than the 31% of unpaid reviews that provided 5-Star ratings.  Despite the difference in population size (94 paid reviews vs. 40,471 unpaid reviews) the percentages of 5-Star between both is different enough between the two to determine positivity bias is present in paid reviews.
</p>
<h3>Additional Analysis Proposal</h3>
<p>
  To further analyze whether or not positivity bias exists in paid reviews, a breakdown of percentage of the remaining reviews by star rating could prove useful (i.e. are the remaining 49% of paid reviews all 4-Stars? Are any of the paid reviews 1-Star? vs. unpaid breakdowns).  Reviewing to see how different each remaining star rating is between paid and unpaid would be useful in providing further assessment as it could allow us to determine the distribution of 3-5 Star ratings in the paid program vs. 1- & 2-Star ratings.
</p>
