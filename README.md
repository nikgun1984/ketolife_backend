<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://ketolifeapp.herokuapp.com/">
    <img src="app/static/images/logo.png" alt="Logo" width="100">
  </a>
  <h3 align="center">Ketolife</h3>
</p>




<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project

![title](app/static/images/screen_shot.png)  
https://ketolifeapp.herokuapp.com/


Welcome to Keto Life website where you can easily find delicious recipes from breakfast to dessert, create new recipes and look up nutritional data of the ingredients. It has never been easier. In the past, i have done various diets and fastings and nothing was working for me until i found out about the Keto diet. I can tell you I saw the results after a couple of weeks. Some diets can be super painful, but not Keto. You can lead a healthy way of life on Keto and still get treats that you would never think are a part of your diet. So what is Keto diet? 

The ketogenic diet is a high-fat, adequate-protein, low-carbohydrate diet that in medicine is used mainly to treat hard-to-control epilepsy in children. The diet forces the body to burn fats rather than carbohydrates. (Wikipedia)

Keto diet is becoming more and more popular among people who want to lose weight and see the results of this diet in just as little as 1 week. This is the main reason i have decided to build this Keto recipe website. 

### Built With

* [Bootstrap](https://getbootstrap.com)
* [JQuery](https://jquery.com)
* [SQLAlchemy](https://www.sqlalchemy.org/)
* [Flask](https://flask.palletsprojects.com/en/1.1.x/)
* [PostgreSQL](https://www.postgresql.org/)
* Edamam and Spoonacular APIs
* Programming languages: Javascript, CSS, HTML for Front-End and Python for Backend
* [Heroku](https://www.heroku.com/)



<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* python3
```sh
pip install freeze
```

### Installation

1. Get a free API Key at [https://developer.edamam.com/](https://developer.edamam.com/) and [https://spoonacular.com/food-api](https://spoonacular.com/food-api)

2. Clone the repo 

```sh
https://github.com/nikgun1984/ketolife_backend.git
```
3. Create virtual environment  
```sh
python3 -m venv venv  
```  
then enter your environment
```sh
source venv/bin/activate
```

4. Install PIP packages 
```sh
pip install -r requirements.txt
```
4. Create ```secrets.py``` and in there enter missing API keys and secret key key_gen(just generate any key using any algorithm)
```JS
# spoonacular_api
APP_KEY = 'YOUR API KEY'

# edamame api
APP_ID_RECIPE = 'RECIPE_ID'
APP_KEY_RECIPE = 'RECIPE KEY'

#Secret Key
key_gen = 'YOUR SECRET KEY' 
```

5. You will need to preload some data to your database from backup.sql file. You can just feed it using the following command:
```
psql < backup.sql 
``` 
6. Run app 

```
flask run
```


<!-- USAGE EXAMPLES -->
## Usage. 

https://ketolifeapp.herokuapp.com/

Keto Life is not only desktop application but also mobile responsive. If you are new to Keto diet you can learn briefly what it 
is about and see foods that you can eat during your diet. There is a long list of products attached to the Home page. You also can find additional information on foods that are not in the list just by going to the Ingredient Nutrition Facts page. Just follow the steps, enter your product in search box, choose units and amounts to get all necessary data to see if it is a Keto food.  
![title](app/static/images/screenshots/2.png)  
![title](app/static/images/screenshots/1.png)  
You can also search for recipe. Just enter keyword or name of the recipe in the search box and find all possible recipes based on your search.  
![title](app/static/images/screenshots/3.png)  
You can add ratings, comments to the recipes. You need to register in order to do that. As a registered user you also can create you recipes and share it with other users to comment on. You can also edit your profile: change your username,email,upload a user profile picture.  
![title](app/static/images/screenshots/4.png)  

The app was created using Javascript (Vanilla and JQuery), HTML,CSS, Twitter Bootstrap for front-end and Python programming language with Flask as framework for backend and SQLAlchemy as ORM. For this application, I used open source relational database PostgreSQL.  
The following is the schema for the Keto Life App  
![title](app/static/images/schema.png)  
<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/othneildrew/Best-README-Template/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Nick Gundobin - [@my_email](https://mail.google.com/mail/u/0/?view=cm&fs=1&to=ngundobin@gmail.com&su=SUBJECT&body=BODY&bcc=ngundobin@gmail.com&tf=1) - ngundobin@gmail.com  
[@my slack](sbcommunity-sec.slack.com/U017AUYK05T) - nick_g(slack)

Project Link: [https://github.com/nikgun1984/ketolife_backend](https://github.com/nikgun1984/ketolife_backend)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [Img Shields](https://shields.io)
* [Recipes Site](https://www.allrecipes.com/)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [Edamame Staff](https://developer.edamam.com/edamam-recipe-api)
* [Springboard Staff](https://springboard.com)
* [othneildrew YOU ROCK!!!](https://github.com/othneildrew/Best-README-Template)
* [Heroku](https://www.heroku.com/)
* [Renish](https://github.com/renishb10)





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/badge/contributors-2-green
[contributors-url]: https://github.com/nikgun1984/ketolife_backend/network/dependencies
[forks-shield]: https://img.shields.io/badge/forks-0-red
[forks-url]: https://github.com/nikgun1984/ketolife_backend/network/members
[stars-shield]: https://img.shields.io/badge/stars-0-blue
[stars-url]: https://github.com/nikgun1984/ketolife_backend/stargazers
[issues-shield]: https://img.shields.io/badge/issues-0-yellow
[issues-url]: https://github.com/nikgun1984/ketolife_backend/issues
[license-shield]: https://img.shields.io/badge/license-MIT-yellowgreen
[license-url]: https://github.com/nikgun1984/ketolife_backend/blob/main/README.md
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/nick-gundobin-5b905931/
[product-screenshot]: images/screenshot.png
=======
