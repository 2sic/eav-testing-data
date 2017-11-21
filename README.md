# eav-testing-data
Database and related material used for running unit tests


## Installation
1. since the DB is included, it will be very large. please install & activate [GIT LFS](https://git-lfs.github.com/) first
1. Download the entire set from Github
1. mount the db in your local sql - I recommend to use the name `eav-testing`
1. mount the site in your IIS with the name `http://eav-testing.dnndev.me`
1. make sure that your DNS or `hosts` file will point *.dnndev.me to your pc
1. adjust the DB connection string in the web.config
1. open the browser to the address, make sure DNN is running and you see a correct site

You are now all set to start running the test sequences for the EAV system



