<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Cookie Monsters
*[Alberto, Emanuele, Javier and not Onur]*

*[Data Analytics, Barcelona & 16/08/2019]*

## Content
- [Project Description](#project-description)
- [Hypotheses / Questions](#hypotheses-/-questions)
- [Dataset](#dataset)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

<a name="project-description"></a>

## Project Description

The scope of this project is to determine the attributes that make a cookie delicious. Based on historical data of 5K cookies regarding baked_temp, sugar_index among others, we develop a Machine Learning model to predict the quality of each cookie. Thanks to this approach, Cookie Flea will be able to develop the perfect cookie recipe for all of us to enjoy. 


<a name="hypotheses-/-questions"></a>

## Hypotheses / Questions

 What is the best combination of attribues to make the perfect cookie?

<a name="dataset"></a>

## Dataset

The dataset is provided by Cookie Flea regarding historical data of 5K recipes with their corresponding quality label.

**sugar to flour ratio** The fraction of sugar to flour, expressed as a decimal (sugar/flour). 

**sugar index** Modified glycemic index. 

**bake temp Baking** temperature, in degrees fahrenheit. 

**chill time** Time necessary for the cookies to rest in the fridge, expressed in minutes. 

**calories** Unit of heat equal to the heat needed to raise the temperature of 1,000 grams of water by one degree Celsius. 

**density** Expressed in grams/cm3. 

**pH** pH of cookie. 

**grams baking soda** Grams of leavening agent (from recipe). 

**bake time** how long the cookies need to bake, in minutes. 

**butter type** Form of butter used. 

**weight** In grams. 

**diameter** In centimeters. 

**mixins** Elements added to the batter, as additions. 

**crunch factor** Index of chrispiness. 

**aesthetic appeal** Appearance, based on color, regularity, and form. 

**quality** ‘Goodness’ of cookie.  (Target variable)


<a name="workflow"></a>

## Workflow

1- Setting up the objective: In this case, extract all the information we can from the given variables to be able to predict the quality of the biscuits

2- Writing down some hypothesis: The higher the sugar the better the quality? What about calories? May be the density is more important than what we thought at first... 

3- Explore the data: Just by with a fast look at the data you can see a ton of interesting things, from the temperature of the oven to the time spent in it

4- Cleaning the data: Of course , not everything is going to be the way it ought to be, and so this dataset had a lot of things but clarity and clearness are not one of them 

5- ML modeling: After we have fixed all the data, it is time to machine learning! So let's drop some overrelated columns, select some features, analyse the result of our recipe and then choose the best model to fit the data

6- Try and check: Then, we applied the mdoel to the dataset and got some interesting results... may be too interesting by the way, so we could try a few models later and we found out that it was even more interesting than we thought at first

7- Conclusion: We did get results, concrete and useful ones, but may be not accurate enough. Probably this model is not enough trained. However, the reason for that may be the that the data is worse than it could be

<a name="organization"></a>

## Organization

1- Trello as our project management tool. 

2- GitHub as our verion control system. 

3- Terminal to communicate with our VCS. 

4- Python as our data wrangling language and visulizations

5- SequelPro to store the data. 

6- Slides as our presentation tool.

<a name="links"></a>

## Links
Include the links to your repository, slides and trello. Feel free to include any other links associated to your project. 

[Repository](https://github.com/albertoabreu91/cookies_project)  
[Slides](https://slides.com/)  
[Trello](https://trello.com/b/BLVhcMqt/datathon)  