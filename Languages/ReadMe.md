# How to add a new translation

1. Translate one of the existing files
    * please don't change the keys :no_good_man:
    * if you can't find your language code [here](https://github.com/DevExpress/DevExtreme/tree/20_2/js/localization/messages) the components don't have appropiate translations for your language. In this case please use *en_full.js* because this is the complete translation file, including some of the component translations.
    * Example:
        * en.js
            * newVersionTitle: "New Version available",
        * de.js
            * newVersionTitle: "Neue Version verfübgar",
2. Save your file with the language code according to ISO 639-1
    * http://www.mathguide.de/info/tools/languagecode.html
        * eg: Languages/fr.js
    * i'm using the code to add the correct flag using this library
        * https://github.com/lipis/flag-icon-css
3. Make a pull request :rocket:
