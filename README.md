Basic Yii2 App Starter
================================

Development Environment
------------------------

To get up and running with the project 
```
# Clone the project
cd ~/projects
git clone git@github.com:badams/yii2-app.git myApp
cd myApp

# Install dependencies
composer global require "fxp/composer-asset-plugin:1.0.0"
composer install

# provision VM
vagrant up

# Add entry to hosts file
echo '192.168.99.100 app.dev' | sudo tee -a /etc/hosts

```

**You can now visit `http://app.dev` in your browser to access the site.**


