# [Desansiedad Data Analysis](#Table-Of-Contents)
This is a data analysis I made to the team of desansiedad, desansiedad is a mexican enterprise that offers online professional treatment for anxiety, their web page and therefore their google analytics is an important asset to analyse, here I did most of the analysis with google data studio, and just a little with python, pandas, matplotlib, numpy. The challenge was on choosing the correct filters, the data was clean by origin.

You can start by reading the results or go directly to the [table of contents](#Table-Of-Contents).

# [Results](#Table-Of-Contents)
You can read the some of the results below or enjoy the entire report by [clicking](https://tinyurl.com/desansiedad).

I will list some of the insights I had for Desansiedad:

*   Our audience is dominated by females, they represent 70% of our audience.
*   The best age range for both genders is 25-34 years, we must focus some of our marketing efforts on those ranges.
*   Other female age ranges are relatively flat, we have the opportunity to offer our product to most of women and hace a clear acceptance of it.
*   Best countries: Mexico, Chile, Spain, Peru, USA.
*   USA we have a big opportunity to take our efforts to USA, every user in USA represents $11 MXN compared to the others best countries that are around $6 MXN, I agreed to not show the exact amount of money they make per country so you won't see the exact insight on the presentation.
*   84% Of our users come from a mobile phone, a web site with responsive design our an application for android and then iOS is a MUST.
*   Our audience is interested in some particular themes like: Travel, wellness, lifestyle, petting, green living.
*   Organic search is our best traffic source, it represents 50% of our traffic followed by social networks that represent 25%. SEO is a must we have to achieve.
*   We must follow marketing campaigns via email and newsletter to keep in touch with our customers, e-mail users stay the most of time within the web site and have the less bounce rate.
*   The best social networks we have impacted are youtube and facebook, content marketing is working there, we should analyse which kind of content represents the most virality and try to replicate it.
*   In our web site there are 1512 pages with more than 99 views, 173 of those pages represent 60% of our total visits. Of those 173 the first 17 ordered by unique visits, represent 26% of the total unique visits within the web site.
*   There are a lot of blogs and tutorials in our page that are not popular in terms of views but according to other metrics like time within page are actually sticky, we have to do something to get that content to the surface.
*   There is a period within the months where the sales can't surpass 200k mexican pesos, that period is between day 8 and 18 of all the months analyzed.


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
