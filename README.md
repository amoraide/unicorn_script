## Introduction
This script is used to restart unicorn instances. Typically useful for when multiple unicorn instances are required.
## Setup
Out of the box, bundler is required. Though the init_unicorn function can be edited in order to run specific commands in order to initialize the unicorn instance.

Within the script, there are 4 variables that need to be set:

1. Set the `APP_PATH` variable to point to your rails application
2. Set the `PID_FILE` variable to point to where your pid file will be placed.
3. Set the `UNICORN_CONFIG` variable to point to your `unicorn.rb` file
4. Set the `RAILS_ENV` variable

## Usage

```
run_unicorn on
run_unicorn off
run_unicorn restart
```
