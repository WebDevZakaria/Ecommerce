<h1> E-Commerce Website with React.js and Django Rest Framework </h1>


<h2>Project Overview</h2>

a full-stack web application designed for online shopping. The frontend is built using React.js to provide a dynamic and responsive user interface, while the backend utilizes Django
Rest Framework to handle data storage, retrieval, and user authentication.

<h2>Features</h2>
<hr/>
Product Catalog: Browse a wide range of products.

User Authentication: Secure user authentication for personalized shopping experiences.

Shopping Cart: Add products to a shopping cart and complete the purchase.

Order Management: View order history and manage orders.

RESTful API: Backend API built with Django Rest Framework for seamless communication with the frontend.

Admin Panel: Manage products, orders, and users through the Django admin panel.

<h2>Getting Started</h2>
<hr/>
Follow these instructions to set up and run the Phone E-Commerce webiste locally on your machine.

first thing to do is to clone repository :

    $ git clone https://github.com/WebDevZakaria/Ecommerce.git
     
    $ cd Ecommerce
    

<h3>Backend Installation</h3>
    
Create a virtual environment to install dependencies in and activate it:

    $ virtualenv venv
    
    $ venv\Scripts\activate
    
Then install the dependencies:

    (venv) $ pip install -r requirements.txt
    
Note the (venv) should be in the front of the prompt. this indicate that the terminal session is in a virtual env

<h3>Frontend Installation</h3>

Navigate to the frontend directory:

      cd frontend
      
Install dependencies:

       npm install 

       

<h3>Running the App</h3>       
<hr/>

Once downloading the dependencies has finished you can start the app by back to main forlder Ecommerce and without running npm start you can just start the django server:

     cd .. 
     
     cd Ecommerce

     (env) $ python manage.py runserver

And go to your browser and navigate to http://127.0.0.1:8000.







