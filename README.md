Download Link: https://assignmentchef.com/product/solved-comp3162-project1
<br>
A large entertainment &amp; bar franchise (Hard Knocks) would like to determine whether now is a good time to expand and which country/region of the world is best to open next. Ultimately, they would like to gain some insights on whether to open their next franchise, based on public sentiments generally and opportunities to maximize profits. They first want to test the pulse of persons in relation to the products they sell (Beverages) which would indicate the current public views towards these products. In addition, they have a large dataset with sales data by region and country for different types of consumer goods (household, cosmetics etc), food and beverage. You will be helping Hard Knocks to make their decision in this project! The tasks required have been broken down in several segments and you will be required to start this week!




<ol>

 <li>Between <strong><u>March 04 &amp; March 09</u></strong> (max. 1 word per day) connect to twitter on two separate days and retrieve 8,000 or more tweets containing one of the words from <strong>a</strong> and one of the words from <strong>b</strong> (total 16,000 tweets). Retrieve tweets for the word from <strong>a</strong> on a separate day from <strong>b</strong>. a) “beverage” or “beer”</li>

 <li>b) “party” or “concert”                                                                                                 <strong>[4]</strong></li>

 <li>For each set of tweets retrieved (a-b above), retain the following features only: <em>text, screen_name, user_id, created_at, favourite_count, retweet_count, location, followers_count, friends_count, account_lang, lang. </em></li>

 <li>Remove all non-English tweets (you must indicate how many tweets were removed).     <strong>[1]</strong></li>

 <li>A tweet is considered a duplicate if the text is the same as another tweet. Remove all duplicate tweets</li>

</ol>

(you must indicate how many tweets were removed).                                                              <strong>[2]</strong>

<ol>

 <li>Write the remaining tweets data to a file (.csv). The csv filename should have the format</li>

</ol>

&lt;keyword&gt;_&lt;date&gt;_&lt;myname&gt;. For example, for tweets on “beverage” retrieved on March 07 by

Anderson would be: beverage_2021Mar07_Anderson.csv                                                       <strong>[1]</strong>




<ol>

 <li>Write code to review and show details of tweets retrieved including number of tweets (after doing 2a-c), screen_name with the most followers, tweet with the most retweets, location from which the most tweets originate. <strong>[7]</strong></li>

</ol>




<ol start="3">

 <li>Between <strong>March 10 &amp; 14</strong>, repeat tasks 1 &amp; 2 above. For task 1, use the other words that were not used during March 04-09 tweet retrieval. That is, if you retrieved tweets using “beverage”, you should use “beer” and if you used “party” now use “concert” for part 1b.</li>

</ol>

Save files using same format (the names will be different given that dates will be different).