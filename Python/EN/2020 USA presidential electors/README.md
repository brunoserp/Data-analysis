<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Voter Turnout Analysis in the 2020 U.S. Presidential Election</title>
</head>
<body>

<h1>Voter Turnout Analysis in the 2020 U.S. Presidential Election</h1>

<p>During the 2020 U.S. presidential election, voter turnout became a major point of discussion. Many Americans chose not to vote, citing logistical barriers, a lack of trust in the electoral system, and dissatisfaction with the candidates. However, some voters were more motivated than ever, feeling that the stakes were personal or that they needed to avoid potential regret. Various demographic groups, such as younger voters and those from lower-income backgrounds, faced more significant obstacles to voting. <a href="https://projects.fivethirtyeight.com/non-voters-poll-2020-election">Text link</a></p>

<p>The analysis was made using Python (Pandas) and aimed to uncover interesting behaviors related to social factors. This analysis was proposed by Universidade de Dados, a group focused on data analysis.</p>

<h2>Data Source</h2>
<p>The data for this analysis was sourced from the FiveThirtyEight GitHub repository: <a href="https://github.com/fivethirtyeight/data/tree/master/non-voters">Non-Voters Dataset</a>.</p>

<h2>Key Findings</h2>
<ul>
    <li>The sample consists of <strong>5,836 interviewed individuals</strong>, with an <strong>average age of 51</strong>. The sample was almost evenly split between genders, with <strong>63% identifying as White</strong>. <strong>40% held a college degree</strong>, and the income groups were nearly evenly divided, with the wealthiest earning above <strong>$125k</strong> and the poorest earning under <strong>$40k</strong>.</li>
    <li><strong>44%</strong> of the sample vote sporadically, <strong>31% always</strong>, and <strong>25% rarely or never</strong>. More educated groups tended to vote more.</li>
    <li>The "Other/mixed race" category represents the wealthiest income group (above <strong>$125k</strong>), while the Black category is the only one where the most representative group earns less than <strong>$40k</strong>.</li>
    <li>Among the most representative income categories within each educational level, college graduates are the wealthiest, while less educated groups are the poorest across all educational levels.</li>
    <li>Voters who vote rarely or never are the only group where the lowest educational level is the most representative.</li>
    <li>Among all party preference groups, Republicans have the lowest percentage of college graduates at <strong>35%</strong>, followed by Democrats at <strong>45%</strong>.</li>
    <li>The average age of individuals intending to vote for Trump is <strong>54</strong>, while for Biden, it is <strong>52</strong>.</li>
    <li>More Republicans intended to vote for Biden than Democrats did for Trump.</li>
    <li><strong>91%</strong> of Democratic voters believe that the election result is important, compared to <strong>88%</strong> of Republicans.</li>
    <li>For <strong>34%</strong> of those interviewed, displaying the American flag is a very important sign of being a good American. This sentiment is strongest among women, White individuals, the least educated group, and Republicans.</li>
    <li>For <strong>47%</strong> of those interviewed, believing in God is a very important sign of being a good American, with similar demographic trends as the flag display belief.</li>
    <li>The average age of individuals who intended to vote was higher than those with other intentions.</li>
    <li>Among individuals who did not intend to vote in 2020 (<strong>8%</strong>), <strong>22%</strong> cited a lack of belief that the political system would serve their needs, and <strong>21%</strong> felt their vote did not matter.</li>
</ul>

<h2>Tools and Libraries</h2>
<p>The analysis utilized the following tools and libraries:</p>
<ul>
    <li><strong>Python</strong></li>
    <li><strong>Pandas</strong> for data manipulation and analysis</li>
    <li><strong>Matplotlib</strong> and <strong>Seaborn</strong> for data visualization, with various visualizations presented as tables and graphs.</li>
</ul>

<h2>Analysis Steps</h2>
<ol>
    <li><strong>Data Exploration</strong>: I began by analyzing the data structure, including checking the number of rows and the dataset's head.</li>
    <li><strong>Data Cleaning</strong>: While I did not check for NaN values due to the dataset containing 128 columns (which would have taken up too much space), I ensured the data was prepared for analysis.</li>
    <li><strong>Visualizations</strong>: Various visualizations were created using Matplotlib and Seaborn to illustrate key findings.</li>
</ol>

<h2>Future Work</h2>
<p>Future improvements may include a deeper analysis of the factors influencing voter turnout and exploring additional demographic variables. Enhanced visualizations could also be developed to better communicate findings.</p>

</body>
</html>
