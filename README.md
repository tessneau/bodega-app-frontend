# 🏬 La Bodega 🏬

La Bodega is an app that emulated the experience of shopping at your neighborhood bodega/ corner store deli. La Bodega talks to it's [backend La Bodega API](https://github.com/tessneau/bodega-app-backend) which contains seeded instances of produce and the ability to manipulate a customer's cart found in the controllers. 

![app runthrough gif](https://giant.gfycat.com/FragrantSkinnyGemsbuck.gif)

## Installation

```
bundle install
rails db:migrate && rails db:seed
rails s
```
Copy the resulting url listed as `Listening on [url]` (often it will be localhost:3000), paste the url into your browser & voila. If there are problems, start by checking that the data has seeded by running `rails c`, then `User.all`

## Usage

* A user can login and signup
* On the Home page, a user can browse through lists of categorized grocery items and add them to their shopping cart
* On the Cart page, a user can pay their cart unless they don't have enough money in their wallet
* On the Profile page, a user can check the total of their prevoious cart, that of their current cart, and their wallet
* Here, a user can add money to their account

## Built With
* [ReactJS](https://github.com/facebook/react) - Frontend Framework
* [Sweet Alert](https://github.com/t4t5/sweetalert)

## 🛒 Future Tasks

- [ ] Implement Stripe

## Authors
* [Tess Neau](https://github.com/tessneau)
* [Daniela Sandoval](https://github.com/daniela-sandoval)

