<h3> Forbes List Of Billionaires For The Year 2018 </h3>
You can download the dataset on <a href = "https://www.kaggle.com/jaytilala/forbes-worlds-billionaires-in-2018/download"> Here</a>
<details>
  <summary>
    <h4>Problem Statements</h4>
  </summary>
      <ol>
        <li>Which Continent has the highest number of billionaires</li>
        <li>Which country has the highest number of billionaires</li>
        <li>Which Continent has the highest number of male and female billionaires</li>
        <li>Which Industry has the highest number of billionaires</li>
        <li>Which Sector has more female billionaires</li>
        <li>The Continent and Country with the highest billionaires have what sector predominantly</li>
        <li>Top 3 Continents to look for investments</li>
        <li>Top 5 Countries to consider investing</li>
        <li>Top 5 industries to consider investing</li>
     </ol>  
</details>
<details>
  <summary>
    <h4>Data Transformation/Cleaning</h4>
  </summary>
    <p>The programming language used for sourcing data and data transformation is python, the IDE used is jupyter notebook. The dataset consists of 2257        rows and 12 columna. The column names include
    </p>
  <ul>  		 	 	 	 	 		 	 	 	
  <li>Rank</li>
  <li>Name </li>
  <li>Age</li>
  <li>Source</li>
  <li>Industry/li>
  <li>Gender</li>
  <li>Continent</li>
  <li>Country </li>
  <li>Headquarters</li>
  <li>State</li>
  <li>Net Worth</li>
  <li>Title</li>
  </ul>
</details>


After going through the process of data cleaning and manipulation of the data set from kaggle, here are the insights I was ablae to gleam from it, to see the manipulation process, please check the .ipynb file.

## SUMMARY
NB: I used the first 100 rows for my analysis. why? you might ask, to allow for encompassing of other countries especially from Africa
Asides the obvious who the richest man was (Jeff Bezos), the following information was made to light:
- Asia as a continent has the highest number of male billionaires and highest number of billionaires
- while North America has the highest female billionaires
- There were no female billionaire from Africa in the top 100, while there were no male billionaire from continent Oceania. 
- Nigeria(Africa) is the only country that produced a male billionaire from Africa by the name Aliko Dangote.
- China is the only country to have female billionaire from the continet Asia
- United States has the highest count of billionaire for both genders {f:4,m:27} as a country

*The plot below shows the count of male and female billionaire per continent*

![Gender_Count_Continent](https://user-images.githubusercontent.com/35836370/151636009-b8c53537-2871-4b53-b29f-d795d18c8c48.png)

- Even thou Asia has the largest number of billlionaires, the total net worth is almost half of that of North America. This is depicted graphically 

![worth_cont](https://user-images.githubusercontent.com/35836370/151636608-34ffa595-7da6-4bdf-b6a2-9458bb819931.png)

With further anaalysis into the continent of North America, it showed USA is the major contributor of about 90% in all

![usa](https://user-images.githubusercontent.com/35836370/151636987-9caeb3c6-c292-48a1-889e-4b2211e2e129.png)

Getting the sum net worth of each gender per country showed USA had the highest networth for both genders

![worth_gen_count](https://user-images.githubusercontent.com/35836370/151637188-bd59a4e1-0743-4e43-865d-9030316f7fff.png)

Taking a look at USA economy, showed that the Technology industry had the highest number of billionaires, followed by Finance and Investment, and then Fashion.

![usa_ind](https://user-images.githubusercontent.com/35836370/151637570-44a1b2c8-cd2f-48e2-9cc2-8a5634bc703a.png)
