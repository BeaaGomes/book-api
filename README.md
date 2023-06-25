# Book API

**This project is the resolution of a technical assessment**  

### Challenge  

Create a book CRUD API with authentication   

## Setup  

Access the api directory  

    cd book-api

Install dependencies  

    composer install  

Copy the example env file  

    cp .env.example .env  

Generate a new application key  

    php artisan key:generate  

Create an empty database and put the access credentials in .env  

Migrate

    php artisan migrate

Run the server locally  

    php artisan serve  

You can now access the server at http://localhost:8000  

There are example requests in the `collection.postman_collection` file

## License  
[MIT](https://choosealicense.com/licenses/mit/)  
