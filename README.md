# fake-bower-assets
Composer package to "replace" bower-asset dependencies that aren't actually needed

## Why?
I use Yii2 a lot, and to use the Gii feature for generating base models.
Gii also has the ability to generate views, but I don't use those. Unfortunately
then Gii requires some bower-asset stuff that often has problems due to the
fxp/composer-asset-plugin.

So this composer.json file says it replaces the jquery packages that Gii needs
to resolve fxp/composer-asset-plugin issues.
