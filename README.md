## Laravel Chatbox

### Notice
- #### Laravel [bug](https://github.com/laravel/docs/pull/6086)
    After creating project,
    ```shell
    $ composer create-project --prefer-dist laravel/laravel [project-name]
    $ composer install
    ```

    it will return an error:
    > mockery/mockery 1.4.2 requires php ^7.3 || ^8.0 -> your PHP version (7.2.32) does not satisfy that requirement.

    **Running `composer update` to solve it.**
