![image](http://i.imgur.com/fmYdpSi.png)

# AITS

This is a work-in-progress for the website of [Alliance of Information Technology Students](https://www.facebook.com/FEUAITS/)

## Developer Notes

This is a Laravel 5.4 + Mysql app so running a local copy should look something like:

    git clone https://github.com/jj6584/AITS.git
    cd AITS
    composer install
    npm install
    cp .env.example .env
    vim .env
    php artisan migrate

and then run the local server. the server is listening at port 8000.



## Deployment

This app has only one main branch, the `master` branch. 

When deploying a new build, test it first in staging
Once verified, you can now deploy it to the production site

As of this writing, only [Joshua Manaol](https://github.com/jj6584) and [Mark John Idio](https://github.com/mrkjohnperalta) have access rights to deploy to the server.
