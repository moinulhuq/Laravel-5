# Laravel-5

Create Model, Controller with resource and migration at a time

# php artisan make:model FireRatingResistance -mcr

# php artisan make:request StoreFireRatingResistance

# php artisan make:export FireRatingResistancesExport --model=FireRatingResistance

-m, --migration Create a new migration file for the model.
-c, --controller Create a new controller for the model.
-r, --resource Indicates if the generated controller should be a resource controller

# if you run php artisan make:model --help you can see all the available options



#find and Kill

sudo lsof -i tcp:3000 

kill -9 <PID>
