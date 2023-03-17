# Deploying HTML to a Heroku App

> **Note**

> Heroku no longer has a free plan. This process will stillwork, but will nto be free. The live links below havebeen deactivated to save cost. 

This sample HTML has been deployed to a Heroky App. This sample HTML is available to view at [https://heroku-deploy-html.herokuapp.com/](https://heroku-deploy-html.herokuapp.com/).

1. Register for a [Heroku account](https://signup.heroku.com/) (you will have to add a payment method).
2. Go to your [Heroku dashboard](https://dashboard.heroku.com/) and create a new app. Give the app a name and choose a location. Click ```Create App```.
3. From what I have research, Heroku is not meant for deploying static HTML. We will deploy our static HTML page by telling Heroku that this is a simple PHP application. Create a new file named ```index.php```. In that file include the following code:

```php
<?php include('index.html'); ?>
```

4. Using Composer, create a new simple ```composer.json``` file. This can be done using the Terminal and ```composer init```, or creating a file names composer.json and adding the following code. 

```json
{
    "name": "thomasa/heroku-deploy-html",
    "type": "project",
    "authors": [
        {
            "name": "Adam",
            "email": ""
        }
    ],
    "require": {}
}
```

5. Install the [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli)
6. 

## Requirements:

* [Heroku](https://dashboard.heroku.com/)

<a href="https://codeadam.ca">
<img src="https://codeadam.ca/images/code-block.png" width="100">
</a>
