<p align="center">
    <a href="https://www.wagento.com/">
        <img src="https://www.wagento.com/static/version1607417403/frontend/Wagento/default/en_US/images/wagento-logo-black.png" width="180px" alt="Wagento" />
    </a>
</p>

ACTIVECAMPAIGN extension for Magento 2.3 and 2.4
<!--Name of the project -->

ACTIVECAMPAIGN extension for Magento 2.3 and 2.4
Compatible with Community Edition, Commerce and Cloud
ActiveCampaign gives you the email marketing, marketing automation,
and CRM tools you need to create incredible customer experiences.
<!-- Write description here -->

## System Requirements
* PHP 7.4
* Magento 2.3/2.4
* Elastic Search 7
* RabbitMQ
<!-- mention all the system requirements -->

## Installation

After purchasing the extension from the [Magento Marketplace], download the zip file and uncompress it. Move files to your Magento app/code relative folder:

    $ mv ActiveCampaign /path/to/your/site/app/code/
    
### Post-Install

After installing the extension for the first time, please run these commands to
enable it:

    $ cd /path/to/your/site
    $ php bin/magento module:enable ActiveCampaign_Core ActiveCampaign_Customer ActiveCampaign_AbandonedCart ActiveCampaign_Order ActiveCampaign_SyncLog

Once you have enabled the extension, please follow the instructions in the
[Post-Install, Post-Update or Post-Uninstall][post]
section to complete the installation process.

## Updating

Please visit the Magento marketplace and check for last releases and download the last release.
Replace old files for the new ones and follow same steps for installation.

## Uninstalling

### Composer

If you've installed the extension manually, run these commands from your
terminal or command prompt to remove its data:

    $ cd /path/to/your/site/app/code
    $ rm -rf ActiveCampaign

## Post-Install, Post-Update or Post-Uninstall

To complete the installation, update or uninstall process, please run these
commands:

    $ cd /path/to/your/site
    $ php bin/magento setup:upgrade
    $ php bin/magento setup:di:compile
    $ php bin/magento setup:static-content:deploy

## Configuration

The settings can configured in the Admin panel at
`Stores > Settings > Configuration > ActiveCampaign`. For detailed
descriptions of the available options, please refer to the User Guide.

## Support

If you experience any issues or errors while using the extension, please open a
ticket by sending an e-mail to [support@wagento.com][Support]. Be sure to
include your domain, PHP version, Magento version, a detailed description of the
problem including steps to reproduce it and any other relevant information. We
do our best to respond to all legitimate inquires within 48 business hours.

## License

The source code contained in this extension is licensed under [version 3.0 of
the Open Software License (OSL-3.0)][OSL]. A full copy of the license can be
found in the [LICENSE.txt] file.

## History

A full history of the extension can be found in the [CHANGELOG.md] file.

## Contributing

We welcome any and all feedback, suggestions and improvements submitted via
email to [support@wagento.com][Support]

## Credits

This extension was developed by Juan Pablo Guzman, Yair García Torres, Rohit Dave, Deexit Sanghani, Riddhi Dhakate, Kushangi Panchal and Carlos Gudiño of [Wagento]
in co-operation with ActiveCampaign.

[Wagento]: https://wagento.com/
[ActiveCampaign]: https://www.activecampaign.com/
[Magento Marketplace]: https://marketplace.magento.com/
[OSL]: https://opensource.org/licenses/OSL-3.0.php
[LICENSE.txt]: ./LICENSE.txt
[CHANGELOG.md]: ./CHANGELOG.md
[Support]: mailto:support@wagento.com?subject=[ActiveCampaign%20Integration]%20
[post]: #post-install-post-update-or-post-uninstall