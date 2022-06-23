## Pre-req

Install npm

```sh
brew install npm
```
![video](https://user-images.githubusercontent.com/10250297/173398724-12cbcc35-81b2-4b08-832d-737b928e960a.gif)


Check if node is installed via

```sh
node -v  || brew install node && node -v                                                           
```

## Installation

Make sure you've got [Node.js installed](https://Node.js.org/en/download/) on your workstation, than open your terminal and type the following command:

- if you're using `npm` (the package manager bundled with `Node.js`):

  ```sh
  npx create-probot-app my-first-app
  ```

- if you're using Yarn:

  ```sh
  yarn create probot-app my-first-app
  ```

and follow the instructions printed on the terminal as you go. `create-probot-app` will then take care of the heavy lifting required to setup a Probot app development environment, with proper folder structure, and even installing all the basic `Probot` dependencies.

![npxcreate](https://user-images.githubusercontent.com/10250297/173399590-882adfbb-c2ab-43d2-a7dd-470e7694366b.gif)



## Configure

Run `npm start` to start the server:

![npmstart](https://user-images.githubusercontent.com/10250297/173401958-5191fb8d-7341-450a-9bd3-e840a6557cfe.gif)

Open the url shown in above step in your browser and follow instructions to register your app.

![register-pro-bot-app](https://user-images.githubusercontent.com/10250297/173406587-b9c9f429-3f5c-4c13-ade2-94d99ef0e70a.gif)


This step will create .env with the following

```
WEBHOOK_PROXY_URL
APP_ID
PRIVATE_KEY
WEBHOOK_SECRET
GITHUB_CLIENT_ID
GITHUB_CLIENT_SECRET
```

## CodeSpaces

[New Codespace](https://github.com/codespaces/new)

![Create CodeSpace](https://user-images.githubusercontent.com/10250297/175279222-ae070e3c-6a4a-4a2a-8d83-57a62001868a.png)


## Reference
[Probot docs](https://probot.github.io/docs) 
