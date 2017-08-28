## Authentication-System

A Laravel-Boilerplate for the Technopathic Full-Stack Web Development series was used in the creation of this site.

This Authentication System is created for Back-End database authentication.

## Getting Started
To reuse this code as a framework, fork this repo and clone it onto your local computer. Then run `composer install` to install all of the necessary libraries.
```
git clone https://github.com/CJacobson1986/Authentication-System.git
cd Authentication-System
composer install
```

From there you should go ahead and generate a Controller `php artisan make:controller AuthController`. Next, you should change the .env.example file name to .env.

To start the server, simply do `php artisan serve`.


## Commands
To generate Controllers:
`php artisan make:controller Controller`

To migrate:
`php artisan migrate`

## Screenshot
![alt text](http://h4z.it/Image/1571ac_ysDataTables.PNG "Capture 1")
![alt text](http://h4z.it/Image/ce0fe3_thSysGetUser.PNG "Capture 2")
![alt text](http://h4z.it/Image/eb51af_AuthSysToken.PNG "Capture 3")

## Author
Christopher Jacobson

## Thanks
Special thanks to Technopathic for his Laravel-Boilerplate and the original build scripts.

## License
MIT
