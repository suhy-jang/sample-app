# Ruby on Rails Tutorial sample application

This is the sample application for
[*Ruby on Rails Tutorial:
Learn Web Development with Rails*](https://www.railstutorial.org/)
by [Michael Hartl](http://www.michaelhartl.com/).


## Technology
- Ruby 2.6.1
- Rails 5.2.3
- Postgresql 10.9
- Sendgrid v3


## Main Features

- Sign up (Create user)
- Log in / Log out (Authentication)
  * session keeps login status during web site opening
  * cookies keeps login status for remembering next time open web browser
- Delete user
  * admin account user can delete any other user
- Email confirm
  * After sign up, user can click the activation link what has been sent through the email
  * When user forget password, they can reset password through sending email confirmation


## Deployment in Heroku

- https://rails-sample-app-suh.herokuapp.com/


## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```

For more information, see the
[*Ruby on Rails Tutorial* book](https://www.railstutorial.org/book).


## License

All source code in the [Ruby on Rails Tutorial](https://www.railstutorial.org/)
is available jointly under the MIT License and the Beerware License. See
[LICENSE](LICENSE) for details.
