# HarvestHub App
HarvestHub is an e-commerce platform that connects small-scale farmers directly with consumers, enabling farmers to sell their products online and consumers to purchase fresh produce directly from the source. The platform is built using Laravel, ReactJS, and MySQL, and is designed to be accessible and user-friendly for farmers and consumers with varying levels of technological proficiency.

# Installation
To install the HarvestHub app, follow these steps:

1. Clone the repository from GitHub:

    git clone https://github.com/Rab-son/harvest_hub.git
2. Install the required dependencies using Composer and NPM:

    composer install

    npm install
3. Copy the .env.example file and rename it to .env. Update the environment variables in the .env file to reflect your local environment settings, such as the database connection information and app URL.

4. Run database migrations and seeders to set up the database tables and initial data:

    php artisan migrate --seed

5. Build the front-end assets using Webpack:

    npm run dev

6. Start the development server:

    php artisan serve

# Features
HarvestHub includes the following features:

* Farmer profiles: Farmers can create profiles on the platform, including information about their farms, the produce they grow, and their contact information.

* Product listings: Farmers can list their products for sale on the platform, including product descriptions and pricing information.


* Order placement: Customers can place orders for products directly through the platform, and track the status of their orders through the app.

* Feedback and ratings: Customers can leave feedback and ratings for products and farmers, helping to improve the quality of the platform and the products offered.