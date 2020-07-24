# JAMStack + Netlify + Astra + Cassandra Example

This is an example React Todo application
using a [DataStax Astra](https://astra.datastax.com/register) free tier database for storage in AWS. 

The project interacts directly with the database from the React frontend and can be deployed on Netlify for free with a few clicks.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/phact/todo-astra-jamstack-netlify) [![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/phact/todo-astra-jamstack-netlify)


## Getting started
1. Create a [DataStax Astra](https://astra.datastax.com/register) Cassandra database (free tier).
2. Clone this repo: `git clone https://github.com/phact/todo-astra-jamstack-netlify`.
3. Install Node dependencies: `npm install`.
4. Build the app: `npm run dev`.

## Things of note:
 - The contents of this repo are based on [Jakes's port](https://github.com/tjake/todo-astra-react-serverless/) of the [TodoMVC code](https://github.com/tastejs/todomvc/tree/master/examples/react) originally written by [Pete Hunt](https://github.com/petehunt).
 - The example is modified from https://github.com/huksley/todo-react-ssr-serverless
