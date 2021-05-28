# [Desansiedad Data Analysis](#Table-Of-Contents)
This is a data analysis I made to the team of desansiedad, desansiedad is a mexican enterprise that offers online professional treatment for anxiety, their web page and therefore their google analytics is an important asset to analyse, here I did most of the analysis with google data studio, and just a little with python, pandas, matplotlib, numpy. The challenge was on choosing the correct filters, the data was clean by origin.

You can start by reading the results or go directly to the [table of contents](#Table-Of-Contents).

# [Results](#Table-Of-Contents)
You can read the some of the results below or enjoy the entire report by [clicking](https://tinyurl.com/desansiedad).

I will explain some of the insights I got, the entire report is too long so hope you enjoy.

Here we can see the distribution of the audience on 2 dimensions the first is the users, so in the overall users we can see that most of our audience are females the ages between 18 and 54 look flat on the overall, of course we have a taller bar on 25-34 years old range, and the lower age range are people older than 55, maybe they are not so familiar with online services but that is an hypotheses what we know is that our most important group is females between 25-34 years old, with a flat distribution on the range 18-54 so they are also our actual audience.
The male distribution tend to the left that means most of their public is young as we expect in an online service, and decreases as their audience is older, here again the biggest audience group is between 25-34 years old. For some reason the male distribution looks smaller than the female distribution, of course the result means that their service excels with women but we can see this as an opportunity to analyse what can we do to attract male audience, of course they also have anxiety issues.

On the second dimension that is revenue (the entire revenue can't be showed) so a part of their revenue labeled with age and gender, it has some surprises, for example we can see that on the male side of the plot male between 25-34 represent 214k in revenue (mexican pesos) that group represents the third group of audience that gives the most revenue, we are finding a niche with 25-34 years in both genders.
As it was expected the females between 25-34 are the most relevant group representing the most revenue.
On the female side we see a similar distribution as in the above plot, the best groups of females are between 18 and 54, but now we can see a pattern that after 34 years old the group's revenue tends to decrease as we can see the lowest are 65 or more years old.
On the male side we see a similar patters as with female revenue, it increases until 34 and then it deacreases. A difference here is the group of males between 18-24 years old they don't represent that much revenue compared to the overall male revenue the opposite with females that 18-24 females are one of the most important groups. 

![1](https://user-images.githubusercontent.com/58957744/117361993-5b8dd200-ae80-11eb-9a13-617bad4f4917.png)


The conversion rate looks slow for the younger people on both genders and then with the females looks flat between 0.13 and 0.15 conversion rate, even with the older people they have, those people buy the product with similar facility as the younger 25-34 females.
On the male side our best groups are between 25 and 44 years old, again the older males tend to don't buy the product.

![2](https://user-images.githubusercontent.com/58957744/117361995-5c266880-ae80-11eb-9afd-7b6b7a249d05.png)

As we can see our best channel for acquisition is organic search that must be enough to put all the attention on SEO Search Engine Optimization. The other channels social and direct come from the content marketing sttrateg in the case of social and simply putting the link in the case of direct. For longer sessions we can see the e-mail newslatter is working as we see the difference in percentage between users and sessions plots on the e-mail data point.

![3](https://user-images.githubusercontent.com/58957744/117361997-5c266880-ae80-11eb-872e-2ea2139bb654.png)

The dispotives our audience uses the most are mobile by more than 1M users, this opens the discussion for an app, and for that we may know the operative system that is android on a 75% and iOS 25%.
The best conversion rate between dispositives is with desktop, but that responds to two reasons, first most of the people comes from mobile and second once they have bought the product they tend to use the pc to connect with their psychologist via online reunions.

![4](https://user-images.githubusercontent.com/58957744/117361999-5cbeff00-ae80-11eb-8e63-f8d0f76ba0fe.png)

I wanted to keep this page, I know it may be too much numbers and information but company was optimizing their website so they asked me to find a good insight from their google analytics that can help them, and after talking closely with the team we had this table as a result, it plots the pages that are below the sea line, but also that have good engagement, it was very helpful for them.

![5](https://user-images.githubusercontent.com/58957744/117362001-5cbeff00-ae80-11eb-8f96-0c57fdbf76ea.png)


# Table Of Contents:
* [Abstract](#Desansiedad-Data-Analysis)
* [Results](#Results)
* [Tools And Libraries](#Tools-And-Libraries)
* [Data Analysis And Wrangling](#Data-Analysis-And-Wrangling)
* [Visualization And Reporting](#Visualization-And-Reporting)

# [Tools And Libraries](#Table-Of-Contents)
* Python 3.7
* Google Colab (Jupyter Notebook)
* Google Analytics
* Google Data Studio
* Excel
* Pandas
* Numpy
* Matplotlib

# [Data Analysis And Wrangling](#Table-Of-Contents)

First the tough wrangling part didn't happen here as soon as google analytics had good quality data, the most related to wrangling were the filters in data studio and an important data analysis with python, pandas,etc for detecting ourliers, quick visualizations and statistical descriptions.

I will show some points of the wrangling and analysis but you can see the entire document [here](https://github.com/JorgePablol/Data-Analysis-Desansiedad-with-Data-Studio/blob/main/Desansiedad%20(1).ipynb) I recommend you to reload if github fails to show it or to download and open it with google colab.

Importing Libraries and some statistical descriptions:

![libraries and stat desc](https://user-images.githubusercontent.com/58957744/116306684-00b2f700-a76b-11eb-9713-2586bc94bc12.png)

Looking for outliers on pages plotting unique visits per page:

![out](https://user-images.githubusercontent.com/58957744/116306685-014b8d80-a76b-11eb-8b47-5ce2f834a790.png)
![out2](https://user-images.githubusercontent.com/58957744/116306688-01e42400-a76b-11eb-846a-f9fb0372d0ce.png)

Statistical description without outliers, and only of blogs only:

![stat](https://user-images.githubusercontent.com/58957744/116306689-01e42400-a76b-11eb-91a3-cb8c10322ab5.png)

Distribution of time in the page

![vz](https://user-images.githubusercontent.com/58957744/116306691-027cba80-a76b-11eb-92b2-035555c34ce6.png)

# [Visualization And Reporting](#Table-Of-Contents)
## This was made entirely [click](https://tinyurl.com/desansiedad) to watch the entire report.
