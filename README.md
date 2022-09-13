![](https://img.shields.io/badge/Microverse-blueviolet)

# Hello rails back-end

> This exercise is about creating a "Hello World" application to display a random message. The back-end is built with Rails and the front-end with React.

> ## The front-end for this api service is [Hello react front-end](https://github.com/rbanos-mv/hello-react-frontend)

## Built With

- Ruby on Rails
- PostgreSQL

### Getting Started

To get a local copy up and running follow these simple steps:

### Prerequisites

- Ruby ruby-3.1.2 installed
- PostgreSQL dbms running

### Setup

- Open your terminal and navigate to the folder you would like to save the project.

- Type these commands into the terminal:

```
git clone https://github.com/rbanos-mv/hello-rails-backend.git
cd hello-rails-backend
bundle install
```

- You will need a `.env` file before you install and run the project. The `.env` file contains environment variables needed to deploy the webpage. There is a commented `.env.example` file you can use as a guide to configure your own. Type the following commands into the terminal (or Git Bash, if using Windows) to create your `.env` file:

```
cp .env.example .env
```

- Edit file .env

  - Provide the values for the variables
    - DATABASE_HOST
    - DATABASE_USER
    - DATABASE_PASSWORD

- Type this commands into the terminal:

```
rails db:create db:reset
```

### Run application

- Type this command into the terminal:

```
rails server
```

- This is an api only application that works together with the [Hello react front-end](https://github.com/rbanos-mv/hello-react-frontend)

## Authors

👤 **Roberto A. Baños Alvarez**

- GitHub: [@rbanos-mv](https://github.com/rbanos-mv)
- Twitter: [@RobertoBanosMV](https://twitter.com/RobertoBanosMV)
- LinkedIn: [Roberto A Baños Alvarez](https://linkedin.com/in/roberto-a-banos-alvarez)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- [Microverse](https://www.microverse.org/) for the motivation.

## 📝 License

This project is [MIT](./MIT.md) licensed.
