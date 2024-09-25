<h1>Voter Intent Analysis During the 2020 U.S. Presidential Election</h1>

<p>During the 2020 U.S. presidential election, voter intent became a major point of discussion. Many Americans chose not to vote, citing logistical barriers, a lack of trust in the electoral system, and dissatisfaction with the candidates. However, some voters were more motivated than ever, feeling that the stakes were personal or that they needed to avoid potential regret. Various demographic groups, such as younger voters and those from lower-income backgrounds, faced more significant obstacles to voting. <a href="https://projects.fivethirtyeight.com/non-voters-poll-2020-election">Text link</a></p>

<p>The analysis was made using Python (Pandas), trying to find behaviors I found interesting to share, mostly related to social factors. This analysis was proposed by Universidade de Dados, a group of data analysis environment.</p>

<h2>Data Source</h2>
<p>The data source is available on GitHub: <a href="https://github.com/fivethirtyeight/data/tree/master/non-voters">FiveThirtyEight Non-Voters Data</a></p>

<h2>Analysis Index</h2>
<ol>
    <li>Knowing the data structure</li>
    <li>Knowing interviewers characteristics
        <ol>
            <li>Race x income</li>
            <li>Education x income categories</li>
        </ol>
    </li>
    <li>General points based on the answers</li>
    <li>Democrats x Republicans</li>
    <li>What is considered a good American?
        <ol>
            <li>Displaying the American flag</li>
            <li>Believing in God</li>
        </ol>
    </li>
</ol>

<h2>Conclusions</h2>
<ul>
    <li>The sample has 5,836 interviewed individuals, with an average age of 51. The sample was almost evenly split between genders, with 63% identifying as White, 40% holding a college degree, and nearly evenly divided into four income groups, with the wealthiest earning above $125k and the poorest earning under $40k.</li>
    <li>44% of the sample vote sporadically, 31% always, and 25% rarely or never. More educated groups tended to vote more.</li>
    <li>The "Other/mixed race" category has the wealthiest income group (above $125k) as the most representative. The Black category is the only one where the most representative group earns less than $40k.</li>
    <li>Among the most representative income categories within each educational level, the college graduates are the wealthiest, while the less educated group is the poorest across all educational levels.</li>
    <li>Voters who vote rarely or never are the only group where the lowest educational level is the most representative.</li>
    <li>Among all party preference groups, Republicans have the lowest percentage of college graduates, at 35%, followed by Democrats at 45%.</li>
    <li>People who intended to vote for Trump have an average age of 54, and 52 for Biden.</li>
    <li>More Republicans intended to vote for Biden than Democrats did for Trump.</li>
    <li>91% of Democratic voters believe that the election result is important, compared to 88% of Republicans.</li>
    <li>For 34% of those interviewed, displaying the American flag is a very important sign of being a good American. Women, Whites, the least educated group, and Republicans are the most likely to agree with this.</li>
    <li>For 47% of those interviewed, believing in God is a very important sign of being a good American. Women, Whites, the least educated, and Republicans are more likely to agree with this.</li>
    <li>The average age of people who intended to vote was higher than the other intentions.</li>
    <li>Among people who did not intend to vote in 2020 (8%), 22% did not plan to vote because they did not believe that the political system would serve their needs, and 21% did not think their vote mattered.</li>
</ul>
