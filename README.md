# Jungle

Jungle is a mini e-commerce application built with Rails 4.2.

This project was developed as part of Lighthouse Labs' Web Development Bootcamp program, and it is focused on learning Rails by example.

Jungle makes use of rspec and capybara for unit and end-to-end testing.

## Final Product

### User navigation
!["User navigation"](https://github.com/danilogondim/jungle-rails/blob/master/docs/navigation.gif?raw=true)

### Login form
!["Login form"](https://github.com/danilogondim/jungle-rails/blob/master/docs/login-form.png?raw=true)

### Admin dashboard
!["Admin dashboard"](https://github.com/danilogondim/jungle-rails/blob/master/docs/admin-dashboard.png?raw=true)

### Admin new product form
!["Admin new product form"](https://github.com/danilogondim/jungle-rails/blob/master/docs/new-product.png)

### Admin products page
!["Admin products page"](https://github.com/danilogondim/jungle-rails/blob/master/docs/admin-products.png?raw=true)


## Setup

1. Run `bundle install` to install dependencies
2. Create `config/database.yml` by copying `config/database.example.yml`
3. Create `config/secrets.yml` by copying `config/secrets.example.yml`
4. Run `bin/rake db:reset` to create, load and seed db
5. Create .env file based on .env.example
6. Sign up for a Stripe account
7. Put Stripe (test) keys into appropriate .env vars
8. Run `bin/rails s -b 0.0.0.0` to start the server
9. To access admin pages, use the username and password set as environment variables

## Stripe Testing

Use Credit Card # 4111 1111 1111 1111 for testing success scenarios.

More information in their docs: <https://stripe.com/docs/testing#cards>

## Dependencies

* Rails 4.2 [Rails Guide](http://guides.rubyonrails.org/v4.2/)
* PostgreSQL 9.x
* Stripe
