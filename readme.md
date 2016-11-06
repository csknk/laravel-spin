Spin up a Laravel Project
=========================
Set up a Laravel project in an Apache server environment.

This script:

- Sets up a directory and environment for your project (project under /var/www/html)
- Downloads and installs a Laravel project to your new project directory
- Creates a new project database
- Configures the local .env file
- Optionally create and enable an Apache virtual host configuration
- Optionally creates a new GitHub repo for your project and make a first commit

## Requirements
- [Composer](https://getcomposer.org/), which should be referenced in your $PATH
- To run the GitHub setup, you need a GitHub token

## Get Started
1. Clone this repo to a suitable location
2. Create a symlink to `laravel-spin` in your $PATH
3. Run the script

Example symlink creation:
~~~
sudo ln -s ~/public-bash-projects/laravel-spin/laravel-spin /usr/local/bin/laravel-spin

# Run the script by entering `laravel-spin` in a terminal.
~~~
