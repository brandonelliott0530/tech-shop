# Tech Shop

---

This app is an example of a back end software that is used to update and store products in a database for the use in an ecommerce website. This program allows the user to view all categories, products, and tags. As well as create, update, and delete categories, products, and tags. This application uses a variety of different node packages. Including mysql, sequelize, express, and dotenv.

## Requirements

---

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```

## Usage

---

To use this application, the user must navigate to the root directory of the application. When in the root, the user must perform an npm install command in the command prompt. This will install the needed node packages. After performing that installation, the user must navigate into the db folder in their terminal, and then open the mysql shell by entering mysql -u root -p and then entering their password. When in the mysql shell, the user must execute the following command: `SOURCE schema.sql` to initialize the database. After creating the database, the user must execute an quit command in the mysql shell. After closing the shell, the user needs to create a .env file, and update it with the appropriate inormation.

```md
DB_NAME='ecommerce_db'
DB_USER=''
DB_PASSWORD=''
```

After updating that information, the user must perform a npm run seed command in the terminal. This will seed the database with information to help the user get accustomed to the application. After performing the seeding, the user needs to then perform a node server.js command in the terminal. This will start the application on port 3001. After starting the application, the user can use a program such as Insomnia to view the data, perform get, post, put, and delete requests.

## Challenges in development

---

The only challenge that I had with developing this program was correctly setting up the index.js file in the models directory. With the help of my instructional staff, I was able to format it correctly.

## Demonstration video

---

[Here is a link to the demonstration video for this program](https://drive.google.com/file/d/1DSVSkhHwpxCuYDRPL1OXf6bV3l3jFbx4/view)

## GitHub repository

---

[Here is the GitHub repository](https://github.com/brandonelliott0530/tech-shop)

### Contact Me

---

Email: brandonelliott0594@gmail.com

GitHub: https://github.com/brandonelliott0530
