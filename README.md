# Strapi & GraphQL & Next & Apollo

### Deploy the backend

To deploy this Strapi instance you'll need:

- [A Heroku account](https://signup.heroku.com/) for free
- [A Cloudinary account for saving images](https://cloudinary.com/users/register/free) for free

Once you have created these accounts you can deploy your instance by clicking on this button

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/itwebtiger/strapi-graphql-next-apollo)

### Deploy the frontend

**Vercel**

  - Log in to Vercel by installing now CLI:

  `npm i -g now`

  - Secure your `API_URL` with now by running the following command:

  `now secret add api-url <https://your-strapi-instance.herokuapp.com>`

You can deploy your app and for this you have two options. But for each one of them, just press enter when the root directory of your code is asked.

  - Execute `now`

  - Or you can simply click on the following button

[![Deploy with ZEIT Now](https://zeit.co/button)](https://zeit.co/new/project?template=https://github.com/itwebtiger/strapi-graphql-next-apollo)

**Netlify**

To deploy this Strapi instance you'll need:

  - [A Netlify account](https://app.netlify.com/signup) for free

Once you have created your account you can deploy your instance by clicking on this button.

[![Deploy](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/itwebtiger/strapi-graphql-next-apollo)

  - Select a repository name and fill API_URL with the url of your Strapi instance on Heroku (eg: https://your-app.herokuapp.com) without the trailing slash

### Features

  - 2 Content types: Article, Category
  - 2 Created articles
  - 3 Created categories
  - Permissions set to `true` for article and category
  - Responsive design using UIkit

### Pages

  - "/" display every articles
  - "/article/:id" display one article
  - "/category/:id" display articles depending on the category

### Getting started

**Clone the repository and install dependencies**

```bash
git clone https://github.com/itwebtiger/strapi-graphql-next-apollo
cd strapi-graphql-next-apollo

# Using yarn
yarn setup:yarn

# Using npm
npm run setup:npm
```

### Scaffold your project

This command will launch both of your backend and frontend servers and do a data migration in your backend server

```bash
# Using yarn
yarn build:yarn
yarn develop:yarn

# Using npm
npm run build:npm
npm run develop:npm
```

Alternatively, you can still start your servers separately:

### Start the backend server

```bash
cd backend

# Using yarn
yarn build
yarn develop

# Using npm
npm run build
npm run develop
```

### Start the frontend server

```bash
cd frontend

# Using yarn
yarn develop

# Using npm
npm run develop
```

Next server is running here => [http://localhost:3000](http://localhost:3000)
Strapi server is running here => [http://localhost:1337](http://localhost:1337)

Enjoy this starter
