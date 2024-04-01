

Grocery Mart

## Tech Stack

| Frontend     | Backend      |
|:-------------|:-------------|
| React        | Node.js      |
| React Router | Express.js   |
| Redux        | MongoDB      |
| Axios        | Stripe       |
|              | SendGrid     |

## Usage

### Clone the Project



**Note:** the `master` branch is the current production build. `releases` contain latest deployment tests. `develop` contains all new features and build.

### Client Side

```bash
$ cd client   # go to the client folder
$ npm i       # install packages
$ npm start   # run the client side statically with react-scripts
```

### Server Side

Create a `.env` file in the server directory and insert the following code. Replace the values with your credentials.

```dotenv
# DATABASE CONNECTIVITY
CONNECTION_URL=

# JWT SECTION
JWT_SECRET_KEY =
JWT_AUTH_TTL = 
JWT_CHECKOUT_TTL = 

# EMAIL SECRETS
SENDGRID_KEY = 

# PAYMENT SECRETS
STRIPE_PRIVATE_KEY = 
```

Start the server

```bash
$ cd server   # go to the server folder
$ npm i       # install packages
$ npm start   # start the server
```

