

![MIT License](https://img.shields.io/badge/AI-%23c83c37
)
![](https://img.shields.io/badge/Langchain-%235ce01f
)
![](https://img.shields.io/badge/MRKL-%231f38e0
)
# DaVinci Dresser/Curie Matcher

Both our DaVinci Dresser and Curi Matcher are build usin [langchain](https://www.langchain.com/) and are based on [MRKL](https://arxiv.org/pdf/2205.00445.pdf) and [ReAct](https://blog.research.google/2022/11/react-synergizing-reasoning-and-acting.html). Both of our AI are capable of understanding all the fashion trends, knows what is trending on social media and also knows the user past purchase history/most viewed item and based on that assist user with there query.

There are two agents:-

1 DaVinci Dresser:- It is capable of understanding the user query and can also understand all the latest trends even the most recent ones, and then it returns the product from a ecommerce website.
Example of query can be "I want something which kim kardashian would wear" or "I want somthing dark academia aesthetic" and it will return the products based on that.

2 Curie Matcher:- It is capable of finding you the matching outfits for anything you have or can find you outfits according to the theme of the place you are going. Basically it is a outfit helper. Example of the query can be "I have black top, what can go with it?" or "I want to dress up like Tom Cruise from last night Academy Awards and I have black pants".
## Screenshots
![App Screenshot](https://lh3.googleusercontent.com/drive-viewer/AK7aPaDXbUPj8XtNm-ggr-DpX_WMrotta8cirXyvPjQ7KO1o362UjHv_8y5iAxPpktQeoWKzeH7B2Rh56eHPD_c-FGsJigyHCA=w1920-h933)
![](https://lh3.googleusercontent.com/drive-viewer/AK7aPaCgMLM3BN9UDLaR9pYbTnhV62_O_npmBI9hbXMWPzOAGB_UGjiYQHy_Anji2JqtrPEUe9xm0XZFVLeP617Sdv9-3QOvjw=w1920-h933)

## Demo
(Note the error on the screen will go away once you insert your API key) 

To view the demo [click here](https://rythmn.streamlit.app/).

## To run locally

To run locally, first clone the repo by
```bash
git clone https://github.com/rythmn1111/DaVinci.git
```
Then navigate to the directory of program
```bash
cd DaVinci
```
Then install the dependency by running
```bash
pip install -r requirements.txt
```
Now simply run, and enjoy :)

```bash
streamlit run test.py
```


