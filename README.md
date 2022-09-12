# E-commerce WebApp

Learn from this [video](https://www.youtube.com/watch?v=YZvRrldjf1Y).  

Build an E-commerce website based on [Django](https://www.djangoproject.com/) and [Python](https://www.python.org/).

If you like this project, please give me a star! Thank you!  

## Project Summary

This item displays the products. Users can add and remove products from the shopping cart, as well as specify the quantity of each item. They can enter their address and select Stripe to process the payment.

## Running this project

To get the project up and running, you should first install Python on your computer. It is recommended to create a virtual environment to store your project dependencies separately. Here it is recommended to install virtualenv.

```
pip install virtualenv
```

After, clone this repository and open it in the editor of your choice. In terminal, run the following command in the project's base directory.

```
virtualenv env
```

Then, you can run the activation command.
```
source env/bin/active
```

Then we can install the project dependencies.
```
pip install -r requirements.txt
```

Now, the project can be run using the command. 
```
python manage.py runserver
```

If you want the payment to work, you will need to enter your own Stripe API key in the `.env` file.

