#Usage

##Clone this repo

        $ git clone git@github.com:Shashikant86/Behat-Appium.git
        $ cd Appium-Behat


## Install Dependencies with Composer 

You need to install [composer](https://getcomposer.org/doc/00-intro.md) and make it global if required.

Now install all dependencies 

         $ composer install 


## Install and launch Appium Server 

You can download appium server with npm. We have package.json file to get that from root of the project. 

      $ npm install 
      $ ./node_modules/.bin/appium

OR 

You can install it globally using 

      $ npm install -g appium 
      

## Configure Simulator Or Real Device 

Next step is to configure, iOS or Android Simulator/Emulator or READ device by referring Appium [Documentation](http://appium.io/slate/en/master/). All the capabilities has been added to MinkExtension 

You need to update 'behat.yml' as per your setup or create multiple profiles. 

## Launch Behat 


Now to launch Behat with default profile 

      $./bin/behat














