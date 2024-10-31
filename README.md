> [!NOTE]
> ### About this repo
> [Latest code](https://github.com/Open-Web-Analytics/Open-Web-Analytics/commit/efb54c4e1ba57fd7d9917be5ecb19c01915ca652) (as of 2024-10-18) from the [official OWA repo](https://github.com/Open-Web-Analytics/Open-Web-Analytics) merged with [modifications](https://github.com/Open-Web-Analytics/Open-Web-Analytics/commit/cdd54ec68805eec5018099dbdc3d0743b84dea37) from [ralfulrich's fork](https://github.com/ralfulrich/Open-Web-Analytics) ([see](https://stackoverflow.com/a/77315015/)) to allow installation on PHP 8.1+.
> ### Installation
> 1. Follow the instructions found [here](https://github.com/Open-Web-Analytics/Open-Web-Analytics/wiki/Installation) but download the latest OWA release from [this fork's releases](https://github.com/aaviator42/Open-Web-Analytics/releases) instead. Simply upload `owa.zip` to your server, extract the files, and go to `owa/install.php` in your browser.  
> [OR]
> 2. Manual install:
>     ```
>     git clone https://github.com/aaviator42/Open-Web-Analytics.git
>     composer install
>     npm install
>     npm run build
>     ```
>     Then upload the files to your server and open `install.php` in your browser.
>
> The [mods](https://github.com/aaviator42/Open-Web-Analytics/tree/mods) branch of this repo additionally contains experiements with non-upstream OWA functionality.
> 
> The original OWA project README follows this notice.
------------


# Open Web Analytics Server

Open Web Analytics is an open source alternative to commercial web analytics tools such as Google Analytics. This software allows you to stay in control of the data you collect about the user of your websites or applications.

This repository installs the OWA Server and Javascript tracking client which can easily be added to web pages. 

- To add OWA tracking to a WordPress based website install the [OWA integration plugin](https://wordpress.org/plugins/open-web-analytics/) or see [this repository](https://github.com/Open-Web-Analytics/owa-wordpress-plugin).
- To add OWA tracking to any PHP application use the [OWA PHP SDK](https://github.com/Open-Web-Analytics/owa-php-sdk)

## Features

- Track visitors, pageviews, e-commerce transactions, and configurable actions
- Track unlimited number of websites using a single instance of OWA Server
- First party Javascript tracker client
- Reporting Dashboard/Portral
- View and customize all reports
- Generate Heatmaps
- Generate "Domstream" session recordings
- Geolocation of visitors
- REST API for administration and data access
- Multi user reporting interface
- Extensible framework via custom modules

## Requirements and Installation

See the [technical requirements](https://github.com/Open-Web-Analytics/Open-Web-Analytics/wiki/Technical-Requirements) before you install OWA Server. A step by step [installation](https://github.com/Open-Web-Analytics/Open-Web-Analytics/wiki/Installation) guide will walk you through how to install OWA.

## Documentation
See the wiki for documentation about the OWA Server and the Javascript Tracker client.

## Issues & Support

Please read the [troubleshooting](https://github.com/Open-Web-Analytics/Open-Web-Analytics/wiki/Troubleshooting) guide before filing any issue or bug reports. Issue tickets without the necessary debug info will be closed automatically.

## Development 

To contribute to the Open Web Analytics for WordPress plugin you need to:

1. Clone the repository
2. Download and install [Composer](https://getcomposer.org/) for managing PHP dependencies.
3. Run `composer install`


## Donate to this project

Open Web Analytics is free.  However, we ask that you donate to the project if you need support. Your donation helps fund the development of this project.

[Donate to the project here](http://paypal.me/openwebanalytics).


## Copyright and License

This project is licensed under the [GNU GPL](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html), version 2 or later.

&copy; [Peter Adams](http://peteradams.org).
