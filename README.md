# WORDPRESS INSTALL TEMPLATE

Download .zip file to quickly setup a **Wordpress** installation.

Run `composer install` to load the required dependencies.

Create a *wp-config.php* file based on *wp-config-sample.php* to define the required constants such as :

- DB_NAME
- DB_USER
- DB_PASSWORD
- DB_HOST
- WP_HOME

Run `wp core install --url=example.com --title=Example --admin_user=supervisor --admin_password=strongpassword --admin_email=info@example.com` to end the website installation.
