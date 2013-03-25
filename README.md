# An intuitive and powerful launcher for Magento admin panel

![Bubble Launcher](http://i.imgur.com/g2buapL.png)

## Features
* Quick access to the launcher via spacebar hotkey (customizable)
* Fast search thanks to client-side indexation
* Use scoped query with keyword auto-suggestion (e.g. config, menu, action)
* Perform common tasks quickly such as "Clear Cache" and "Reindex All"
* Default indexers: menu, config, actions
* Other available indexers (disabled by default): products, categories, customers, orders, promotions, attributes
* Add your own logic easily by writing custom indexers and actions

## Installation

### Magento CE 1.6.x, 1.7.x

Install with [modgit](https://github.com/jreinke/modgit):

    $ cd /path/to/magento
    $ modgit init
    $ modgit -e README.md clone launcher https://github.com/jreinke/magento-admin-launcher.git

or download package manually:

* Download latest version [here](https://github.com/jreinke/magento-admin-launcher/archive/master.zip)
* Unzip in Magento root folder
* Clean cache

Full overview available [here](http://bubbleco.de/en/2013/03/25/a-powerful-launcher-for-magento-admin-panel/)