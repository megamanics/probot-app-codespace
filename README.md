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


## Reference
[Probot docs](https://probot.github.io/docs) 
