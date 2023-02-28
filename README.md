# Okta Promos API

![Ice Icon](img/IceIcon_120px.png)

## Run this App Locally

1. Install `git` and `node` in your computer.
2. Clone this repo:
   `$ git clone <URI>`

3. Install Node dependencies:
   `npm install`

4. Run the project:
   - without APIAM: `npm start`
   - with APIAM:
     - Set up custom scopes in your AuthZ server
     - set Issuer to your OAuth endpoint
     - Set Audience to `http://localhost:8081`

## Run on Glitch

1. Remix this project
2. Set Issuer to your OAuth endpoint
3. Set Audience to your Glitch URL
