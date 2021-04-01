# Ignews Project

A blog project with payed subscription option.

## How to run locally

- Clone this repository: `git clone <THIS_REPOSITORY_URL>`
- Enter in folder app: `cd ignews`
- Now, install dependencies: `yarn`
- After, make accounts in Fauna DB, Github, Stripe and Primisc.
- Get all credentials in this services. To see what credencials to get, look the _.env.example.local_ file.
- Fill the _.env.example.local_ file.
- Rename the _.env.example.local_ file to _env.local_
- Type `yarn dev` in your terminal.
- Now you can:
  - Login with github
  - Subscribe with stripe payment option (use 4242 4242 4242 4242 credit card to test)
  - If logged and with a active subscription you can see full posts
  - If not logged of with a inactive subscription you can see just the begining of the posts

## Credits

- Rocketseat Ignite Bootcamp: https://rocketseat.com.br/
