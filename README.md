# my_app

This is a project written using [Lucky](https://luckyframework.org). Enjoy!

## Setting up the project

### With Docker:

* Build:

    ```
    docker-compose build
    ```

* Start the app:

    ```
    docker-compose up
    ```

* Browse to: http://127.0.0.1:3001
  ![docs/screenshots/0.initial_root_page.png](docs/screenshots/0.initial_root_page.png)

* Click `View Your New App`

* (1st time) Sign Up to create a Login:
  ![docs/screenshots/1.SignUp_page.png](docs/screenshots/1.SignUp_page.png)

* This will redirect you to your `me` profile page:
  ![docs/screenshots/2.me_page.png](docs/screenshots/2.me_page.png)

### 'Traditional' way (without Docker):

1. [Install required dependencies](https://luckyframework.org/guides/getting-started/installing#install-required-dependencies)
1. Update database settings in `config/database.cr`
1. Run `script/setup`
1. Run `lucky dev` to start the app

## Learning Lucky

Lucky uses the [Crystal](https://crystal-lang.org) programming language. You can learn about Lucky from the [Lucky Guides](https://luckyframework.org/guides/getting-started/why-lucky).
