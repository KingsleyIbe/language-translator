# LANGUAGE TRANSLATOR APP

The Language Translator App is a rails application that allows users to translate any language into other languages of their choice. The application provides the user with over one hundred languages and utilizes various endpoints.

#### Budget App Screenshots

<table>
  <tr>
    <td>Translator App</td>
    <td>Translated</td>
  </tr>
  <tr>
    <td><img src="./app/assets/images/translate.jpeg" width=256 height=493></td>
    <td><img src="./app/assets/images/translate1.jpeg" width=256 height=493></td>
  </tr>
 </table>

 # Live Demo

 [Live Demo Link](https://language-tanslator.herokuapp.com/)

# Getting Started


_To get a local copy up and running follow these simple steps._

1. Clone the repo
   ```sh
   git clone https://github.com/KingsleyIbe/language-translator.git
   ```
2. Goto project directory
   ```sh
   cd budget-app
   ```

3. Configure `database.yml` in the config folder according to your postgreSQL configuration
4. Run app
   ```sh
   rails server
   ```
   or
   ```sh
   rails s
   ```


# Testing

`bundle exec rspec` will run all the tests.

Also, you can run `bundle exec rspec spec/` to run specific tests.

You can also run `RAILS_ENV=test rspec spec/` to run the tests in test mode.

## Errors

If you encounter any errors, run the following commands.

- Run `rails db:drop db:create db:migrate` to drop, create and migrate a new database.

- Run `rubocop && rubocop -A` to check for and fix code errors.

# This project was built with

- Ruby on Rails

- PostgreSQL

- Bootstrap CSS Framework

# Author

👤 **KingsleyIbe**

- GitHub: [KingsleyIbe](https://github.com/KingsleyIbe)

- Twitter: [Twitter](https://twitter.com/ibekingsley2)

- LinkedIn: [LinkedIn](https://www.linkedin.com/in/kingsley-ibe/)

# 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/KingsleyIbe/language-translator/issues).

# Show your support

Give a ⭐️ if you like this project!

# Acknowledgement

- Hat tip to anyone whose code was a source of inspiration.

# 📝 License

This project is [MIT](./MIT.md) licensed.