[![Netlify Status](https://api.netlify.com/api/v1/badges/77fb5ebc-dd1c-47d6-82f3-5f85c71f509f/deploy-status)](https://app.netlify.com/sites/tmav-cp/deploys)

# TMAV-Website-Dev
TMAV Development Website

## Official Website

[TMAV Website](https://tmav.netlify.app)

## Development Website

[TMAV Development Website](https://tmav-cp.netlify.app)

## Build

The website is developing in PHP, and then built into HTML files for static hosting.

The PHP files are stored within the /views folder. For development, the PHP can be run locally using: 

```php -S localhost:8000```

It will use the index.php file for routing. Netlify HTML routing is done through the _redirects file.

For building to HTML files:

```./build.sh```

The build script will build and move all files to the /public_html folder


## Deployment

Committing to `master` will automatically trigger the Netlify production build and will deploy the site to [https://tmav-cp.netlify.app](https://tmav-cp.netlify.app) 
