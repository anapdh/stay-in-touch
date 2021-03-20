![](https://img.shields.io/badge/Microverse-blueviolet) ![](https://img.shields.io/badge/RoR-red)

# Scaffold for social media app with Ruby on Rails

This repo presents a social media app called “Stay in touch”.

As a guest user:

- I'm able to create account/log in.

- I can see only “Sign in” and “Sign out” page.

As a logged-in user:

- I'm able to see all users list.

- I'm able to see selected user page with their user name and all posts written by them (the most recent posts on the top).

- I'm able to send a friendship invitation.

- I can see a button “Invite to friendship” next to the name of user who is not my friend yet - on both users’ list and single user page.

- I'm able to see pending friendship invitations sent to me from other users.

- I'm able to accept or reject friendships invitation.

- I'm able to create new posts (text only).

- I'm able to like/dislike posts (but I can like single post only once).

- I'm able to add comments to posts.

- I'm able to see “Timeline” page with posts (with number of likes and comments) written by me and all my friends (the most recent posts on the top).

- Timeline is the root page of the app.

- Confirmed friendships creates 2 rows in the query.

## Built With

- Ruby v2.7.0
- Ruby on Rails v5.2.4

## Live Demo

[Stay In Touch](https://stay-in-touch-2021.herokuapp.com/)


## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

Ruby: 2.7.2
Rails: 5.2.4
Postgres

### Setup

Install gems with:

```
bundle install
```

Setup database with:

```
   rails db:create
   rails db:migrate
```

### Usage

Start server with:

```
    rails server
```

Open `http://localhost:3000/` in your browser.

### Run tests

```
    rpsec --format documentation
```
## Authors

👩🏼‍💻 **Ana Paula Hübner**

- GitHub: [@anapdh](https://github.com/anapdh)
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/anapdh)
- Twitter: [@dev_anahub](https://twitter.com/dev_anahub)

👤 **João Paulo Dias**

- GitHub: [@jpdf00](https://github.com/jpdf00)
- Twitter: [@jpdf00](https://twitter.com/jpdf00)
- LinkedIn: [João Paulo Dias França](https://linkedin.com/linkedinhandle)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check the [issues page](https://github.com/jpdf00/ror-social-scaffold/issues).

## Show your support

Give a ⭐️ if you like this project!

## 📝 License

This project is [MIT](./LICENSE) licensed.

