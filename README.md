# comp598-homework-1-solved
**TO GET THIS SOLUTION VISIT:** [Comp598 Homework 1 Solved](https://www.ankitcodinghub.com/product/comp598-homework-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91379&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Comp598 Homework 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
The goal of this assignment is to work through the data-handling phases of a mini data science project to put into practice the ideas we’ve discussed in the Unit 1 lecture. You are welcome to complete the exercises in this homework using whatever tools and programming languages you deem fit. In order to make ANY points, your assignment MUST pass the Homework 1 grading tests. Please watch the orientation video under Lecture Recordings in MyCourses for more information.

In this assignment, you will conduct an analysis of tweets produced by Russian trolls during the 2016 US election. These tweets were published by 538. You can read about them here.

In this mini-project, we’ll be assessing the frequency with which troll tweets mention “Trump” by name.

1. Data Collection

<ol>
<li>Download the raw tweet data. You will ONLY be using the data from the first file(IRAhandle_tweets_1.csv).</li>
<li>Looking at only the first 10,000 tweets in the file, keep those that (1) are in English and (2) don’tcontain a question. This will be our dataset. To filter the right tweets out, take a look at the columns.
i. There are specific columns that call our language. You can trust these.
</li>
</ol>
ii. Assume that a tweet which contains a question contains a “?” character.

c. Create a new file (I would suggest in TSV – tab-separated-value – format) containing these tweets.

2. Data Annotation

<ol>
<li>To do our analysis, we need to add one new feature: whether or not the tweet mentionedTrump. This feature “trump_mention” is Boolean (=”T”/”F”). A tweet mentions Trump if and only if it contains the word “Trump” (case-sensitive) as a word. This means that it is separated from other alphanumeric letters by either whitespace OR non-alphanumeric characters (e.g., “anti- Trump protesters” contains “trump”, but “I got trumped” does not).</li>
<li>Create a new version of your dataset that contains this additional feature.</li>
</ol>
3. Analysis

<ol>
<li>Using your newly annotated dataset, compute the statistic: % of tweets that mention Trump.</li>
<li>It turns out that our approach isn’t counting tweets properly … meaning that some tweets aregetting counted more than once. Go through and look at your annotated data. Identify where the counting problem is coming from.</li>
</ol>
Submission Instructions

Download the template code from https://github.com/druths/comp598-2021 .

Your submission should pass the unit tests and contain – at minimum – the following:

<ul>
<li>– &nbsp;README.md (5 pts)

o In3sentencesorless,explainwherethecountingproblemiscomingfrom.</li>
<li>– &nbsp;dataset.tsv (20 pts)

o ThisshouldbetheoutputofyourDataAnnotationphase.

o Formatistab-separatedvalue,utf-8(aslongasyoudon’tdoanythingfancy,itwillbeinutf-8)(5</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
COMP 598, Fall 2021

</div>
</div>
<div class="layoutArea">
<div class="column">
pts)

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
COMP 598, Fall 2021

o Thefirstlineshouldbeaheaderline(3pts)

o Thefileshouldcontainthefollowingcolumns,inthisorder:tweet_id,publish_date,content,and

trump_mention. Tweets should appear in the same order they appeared in the original file from

538. (12 pts) – results.tsv

o Formatistab-separatedvalue

o Thefirstlineshouldbeaheaderline,withheaders“result”and“value”.

o The second line should contain the result for “frac-trump-mentions”. If necessary, truncate your

answer to three decimal places.

For partial credit purposes, you may also include the code that you used to do this work. It must be readable in a standard text editor. Remember that code readability and partial credit are correlated “#$%

</div>
</div>
</div>
