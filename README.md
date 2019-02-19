Simple React Application for backend and frontend using react and mongodb

1.use command below to create a react application
### `create-react-app`
2.created a server folder
3.We will start by creating our database Schemas. Note, we are using mongoose, a MongoDB connection utility. Let’s touch some files:

### `touch server/models/Article.js`
### `touch server/models/User.js`

We will be using two Schemas Article and User.Article represents articles and User represents users


Editted the two files for articles and user schemas
Create controllers

Looking at the article.ctrl.js ,we have CRUD functions and helper functions: getArticle, addArticle, getAll, clapArticle, commentArticle.