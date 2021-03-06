# nyu_cusp_capstone
Documentation and code for NYU Center for Urban Science + Progress capstone project "Preserving NYC Nightlife Culture Post-COVID-19"

This Read Me has the Abstract and 6 Main Process Maps that document the code and source files used in this project.
Data pertaining to the LiveXYZ dataset cannot be publicly shared. For access, please request NYC Mayor's Office of Media and Entertainment (MOME) under their Department of Nightlife.

# Project Abstract
New York City nightlife is a bustling $35.1 billion industry with world-renowned culture and community that draws people from all over the world (NYC MOME, 2019). With rising rent costs, gentrification, and most recently, Covid-19 shutdowns, the NYC Mayor’s Office of Media and Entertainment (MOME) is exploring supportive policies that can help the nightlife industry recover, adapt, and thrive for years to come. By analyzing MOME’s Covid-19 survey and incorporating neighborhood factors known to affect the well-being of the nightlife industry, the team will develop an interactive dashboard that displays the neighborhoods predicted to be at highest risk of experiencing permanent nightlife cultural loss. Additionally, text analysis of widely used sources describing local nightlife will reveal each neighborhood’s defining cultural characteristics, thus contextualizing and humanizing potential losses.

# 1. <h1> LiveXYZ data (provided by MOME) and Yelp Data (scraped publicly with APIs) were the initial phases of our project.
Through exploratory data analysis, the group was able to glean insight on text analysis to help build neighborhood profiles for the focus regions in NYC. 

![Live XYZ Read Me](https://user-images.githubusercontent.com/58189651/87869546-880a4900-c955-11ea-8e6f-908da5c7d68d.png)

# 2.
![Yelp Read Me](https://user-images.githubusercontent.com/58189651/87869610-fd761980-c955-11ea-9790-67d0daea139f.png)


# 3. <h1> Yelp reviews were then used to perform Sentiment Analysis.
Sentiment Analysis allows the team to determine how positive/negative/neutral patrons felt toward venues in each of the 17 target neighborhoods.

![Sentiment Analysis Read Me](https://user-images.githubusercontent.com/58189651/87869621-0ebf2600-c956-11ea-839d-bb0d56fc55b9.png)


# 4. <h1> 5 Features were then determined to be measured as both a means for displaying neighborhood characteristics as well as their risk likelihood. 
Risk is measured on a relative basis and is a percentage indicating how likely a neighborhood might experience permanent nightlife cultural loss.

![5 Features Read Me](https://user-images.githubusercontent.com/58189651/87869641-2dbdb800-c956-11ea-8fc8-9b55a17319e7.png)


# 5. <h1> These features were calculated in both the Risk Input Model and Neighborhood Profile python notebooks. 
The Dashboard visualization shows the inputs into the each of the respective notebooks, and the resulting csv's were used to build interactive dashboards through Tableau as well as inputs for machine learning tools.

![Dashboard Read Me](https://user-images.githubusercontent.com/58189651/87869645-3a421080-c956-11ea-83d6-6ab243cfe308.png)

# 6. <h1> The Analysis visualization shows the 2 main analytic components used after determining risk and neighborhood profile - Decision Tree and Clustering.
A Decision Tree notebook employing regression analysis helped determine which features were most important at influencing risk, while unsupervised learning techniques through Gaussian Mixture Models clustered the neighborhoods to see if how neighborhoods clustered together.

![Analysis Read Me](https://user-images.githubusercontent.com/58189651/87869649-4332e200-c956-11ea-945f-7b40cf7c71f1.png)
