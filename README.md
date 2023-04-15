# Intructions on running the codes:
1) Download the project jupyter notebook file.
2) Download the given csv file
3) Upload or open both jupyter notebook file and the csv file to Anaconda or Google Colab or any other python IDE.
4) Run the codes, make sure that the csv file is uploaded properly or the proper fila path for the csv file is given.
# FIFA-World-Cup-2022-player-s-performance-analysis
# In last year, FIFA World Cup, which is called the Greatest Show on Earth took place from 20th November 2022 to 18th December 2022 which was hosted by Qatar where 32 teams from all over the world took part in it to win the World Cup and finally Argentina won this competition by beating France football team.
# I have found out Top 10 players from each category like Strikers, Midfield players, Defensive players and Goalkeepers to suggest football clubs which player's to recruit in their teams. I have also answered some of the debated and most discussed topics about this World cup to the football fans from Data Analytics point of views.
# Background Information : 
Total 32 countries competed
16 of them made it to the Round of 16 
8 of them played the Quarter finals
4 to the Semi finals
Final is played between Argentina and France where Argentina won the World Cup.
# Dataset: The dataset is named as players_list.csv which have been collected from https://www.kaggle.com/datasets/tittobobby/fifa-world-cup-2022-player-stats
# Features of the dataset:
The dataset contains 680 rows and 42 columns in total.
The rows contain the specific information of a player based on different attributes in the columns. I have taken into consideration different attribute columns for meaningful analysis. 
# I saw that there are some null values in various columns but it is common because in football players play as per their positions and roles in the field, it is common that a player from a specific position will not show all attributes as for Example player "Nicolás Otamendi" is a player in the defense (DF) position, so his goals (Gls) are showing 0 and it is normal for a player not to score goals but to prevent goals and that's why his blocks, clearances are showing values.
# First, we tried to find out the top 10 players who scored highest goals individually
Kylian Mbappe from France have scored the highest 8 goals.
Then Lionel Messi of Argentina scored 7 goals and he is in the 2nd position.
Julian Alvarez and Oliver Giroud scored 4 goals each and are in 3rd and 4th positions, respectively.
Then I deep dived and took Goals, Assists, Shots, Passes completed, Touches and Successful Dribbles as attributes to find out who were the most “Complete players” and plotted a Radar chart. I plotted Radar chart because in sports analytics it is often used to compare multiples players based on multiple attributes. 
Kylian Mbappe is the player who had most goals, completed most dribbles successfully and had most shots amongst the players.
Lionel Messi had the 2nd highest goals, most assists, had the most passes completed and most touches on the ball amongst the players.
No other forward players went nearly to the performance of Kylian Mbappe or Lionel Messi in this case when considered the above attributes
# FIFA awarded Lionel Messi the ‘Golden Ball’ Award for the FIFA 2022 Football World Cup which is given to the best player of the tournament. Many football fanatics raised questions against it because the competition of the performance between Lionel Messi and Kylian Mbappe was awesome as they went toe-to-toe and very tough. Still, we can see that Mbappe had most goals, successful dribbles and most shots but Lionel Messi had most assists, most passes completed, most touches, he is only 1 goal short then Mbappe, and finally he had nearly as many shorts as Mbappe. Moreover, Lionel Messi became the FIFA World Cup winner this time. If we compare the contribution of Lionel Messi to Argentina team's overall performance, we can see that he also outperformed Kylian Mbappe because Messi contributed more to the success of his team but compared to that Mbappe contributed less which was a crucial factor behind the secret of Argentina's World Cup win. So, I think FIFA awarded the Golden Ball to Lionel Messi when considering this facts and was a fair decision.
# Though the forwards win the best player awards and most other awards historically, midfield players are the unsung heroes of the game because without midfield, a team cannot win.
I took Assists, passes completed, successful tackles, interceptions, touches to the ball, crosses and aerial dual won which are the features of a midfield player and plotted a parallel coordinate plot because parallel coordinate plots are used to compare multiple attributes in football analytics. 
Antonio Griezmann from France topped the chart whereas Enzo Fernandez from Argentina was 2nd, the Dutch midfielder Frankie De Jong is in the 3rd and so on.
# Defense is very important for a team’s success
As a great football manager Sir Alex Ferguson said, “Attack win you matches, and defense win you the tournament. Defenders and Goalkeepers are the foundations of a team’s defense.
Successful tackles, Interceptions, Blocks, Clearance and Aerial duo won are taken as defenders attribute. I choose stacked bar plots here because it is simple and easy to interpret and yet powerful visualization.
Achraf Hakimi, Theo Hernandez and Daley Blind were some fantastic defenders in the world cup.
# Now while finding out the top goalkeepers, I took Minute played, Error, aerial duo won, number of red and yellow cards and passes completed as attributes as those indicated the longer playing capabilities, less error prone and discipline of a goalkeeper. I choose line plots here because it is simple and easy to interpret.
Dominik Livakovic and Emiliano Martinez dominated the competition of being the best goalkeepers in the world cup.
# Does Age matters in Football?
This is a long-discussed question amongst the football fans. 
Football is a physically demanding game where Age must have a meaningful contribution.
But we saw many players have played for longer in their career even in their late 30s also.
I first plotted a box plot and a bar chart to see the Age distribution in all the teams.
Then I found out the top 10 youngest and 10 most old teams, then plotted line plots to see total goals scored and total attempted shots by the youngest and oldest teams by mean age to compare them against the bar plots of ages to see which portion performs better. Found out the younger teams like France outperformed the oldest and experienced teams like Brazil or Belgium which indicates that Age matters in Football.
# At the end, I was able to find out top players from different field positions and recommend them to my clients to recruit.
Able to answer some questions of the football fans after analyzing the and scrutinizing the facts.
As a football fan, it was satisfying for me.
# Key learnings:
Application of visualizations in football analytics.
Story telling.
Insight on performance of different players in the FIFA World Cup 2022.
# Future Work:
A lot of different insights can be found out and variety of visualizations can be tried accordingly to more detailed dataset and this can be used to analyze different player’s performance in different matches as well if more detailed match by match data can be found.
# Please note that the interactive plots are showing in the originial notebook and in google colab also but not showing in GitHub so I have added the .png files for those interactive plots.
# The Google Colab link for this project is:
https://colab.research.google.com/drive/1k7_-X5HHPp5dJPOGq4hV-NyA0B_0MGpl?usp=sharing
# Thank you all








