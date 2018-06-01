# Provider extension for TYPO3 CMS

For a quick and clean start to a new TYPO3 project.

#### Many settings are already integrated and may only need to be activated and adjusted:
* example Template width backend layouts
* different menus (only TS by now)
* meta information
* CSS and JS integration
* spam protection
* website performance via applicationContext
* language settings
* disable default content elements via Extension Manager
* Gridelements incl. example
* Google Analytics (anonymize_ip & opt-out)
* Realurl
* prepared for the integration of own `ext:form` and `ext:news` templates

## How to use:

Just copy the `provider` folder inside typo3conf/ext/ of your typo3 installation and start the integration of your templates.
If you use ext:news with own templates and/or the form core extension you copy these extension templates into Resources/Private/News and/or .../Form.

System environment:
* typo3 8.7.15 - 8.99



#### Thanks to
* Wolfgang Wagner for inspiration in the way of working with provider extensions.
	*  https://wwagner.net/lp/videotraining-typo3-8-lts/kaufen/
* AnalogDE and Boris Schauer for the idea of how to unable the default TYPO3 content elements and for some future ideas.
  * https://github.com/Startpiloten
