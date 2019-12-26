# StravaCsvUploader

Upload a CSV containing activities to your Strava account

## Set up

Run `composer install` in the root folder. This will bring the dependencies and autoloader in. 

Create a .cred file with your data (copy from .cred.example). Obtain those credentials from here: https://www.strava.com/settings/api

Run a the code on a PHP server. If you have `php` command on your localhost then: `php -S localhost:8080` and then set `localhost` as callback domain in the link above.


## Example (index.php)

First, you will need to authorize the app once set up.
Follow the instructions for the file format, attach it and click on submit.

Find a sample file in the **upload** folder.
