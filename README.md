# E-commerce Back End Starter Code

##### Table of Contents

[Description](#description)  
 [Installation](#installation)  
 [Usage](#usage)   
 [Video Walkthrough](#video-walkthrough)   
 [Contributions](#contributions)  
 [Tests](#tests)  
 [Questions](#questions)  
 [License](#license)

## Description

This is project is the backend for an e-commerce website, built using Express.js and Sequelize ORM. It provides the necessary API routes for managing categories, products, and tags.

## Installation

1. Clone the repository.
2. Run npm install to install dependencies.
3. Create a .env file in the root directory and add the following variables:

```
DB_NAME=your_database_name
DB_USER=your_mysql_username
DB_PASSWORD=your_mysql_password
```

4. Run the following commands to set up the database:

```
npm run schema
npm run seed
```

<img src='./public/images/ecommerce-db.png' width=300>

## Usage

To start the server, run the command:

```
npm start
```

Alternatively, if in development, run the command:

```
npm run watch
```

The API will be accessible at http://localhost:3001.

## Video Walkthrough
A video demonstration of the setup of this application and how to access the API routes can be found here:

[Video Demo](https://drive.google.com/file/d/1f3Bel3NX12dO5Mru1oFFyy66Nf2y1vON/view?usp=drive_link)


## Contributions

Github user [Xandromus](https://github.com/Xandromus): [Starter Code Repo](https://github.com/coding-boot-camp/fantastic-umbrella)

## Tests

Use [Insomnia Core](https://insomnia.rest/) to test the API routes.

1. Open Insomnia Core.
2. Import the Insomnia Core workspace containing the API requests.
3. Test the API requests for categories, products, and tags.

<img src='./public/images/get-all-products.png' width=450>  
<img src='./public/images/get-single-product.png' width=450>  
<img src='./public/images/create-product.png' width=450>  
<img src='./public/images/update-product.png' width=450>  
<img src='./public/images/delete-product.png' width=450>


## Questions

For any questions regarding the repository, contact me via:

- Github: [dgomie](https://www.github.com/dgomie)
- Email: <a href="mailto:danny.f.gomez@gmail.com">danny.f.gomez@gmail.com</a>

## License
