
A secondary goal of SpeckCommerce is to be an exemplary model of the powerful
new module system in Zend Framework 2.

Requirements
------------

The dependencies for SpeckCommerce are set up as Git submodules so you should not have to mess with dependencies.

* PHP 5.4+ (With short tags enabled)
* [Zend Framework 2](https://github.com/zendframework/zf2) (latest master)
* [ZfcBase](https://github.com/ZF-Commons/ZfcBase)
* [ZfcUser](https://github.com/ZF-Commons/ZfcUser)
* [SpeckCatalog](https://github.com/speckcommerce/SpeckCatalog)
* [SpeckCart](https://github.com/speckcommerce/SpeckCart)


Why Zend Framework 2?
---------------------

Simple: The ZF2 module system is awesome and provides the perfect foundation for
a project with goals such as ours.

Installation
------------

* Run `git clone https://github.com/speckcommerce/speck.git` and
  set up a vhost pointing to the public directory.
* Install with Composer -- http://getcomposer.org
  * `cd speck && ../composer.phar install`
* Launch the app from the browser, you will be propted for db info/etc
  * installation module is somewhat fragile, please add issues/pull requests at http://github.com/speckcommerce/SpeckInstall
