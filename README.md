# TezBox Languages

This repo contains the main languages translation files used for TezBox. Feel free to work on translations and push updates (spelling mistakes, changes etc), or add new translations.

## New Translations

Simply duplicate the english.json file and rename it to the language you are translating too. Ensure the object keys/IDs are maintained, and only translate the value. E.g.
```
{
...
"error_please_enter_your_seed_words" : "Please enter your seed words"
...
}
```

You will leave **error_please_enter_your_seed_words** as it is, and just translate **Please enter your seed words**

## Variable Replacements

Some of the strings have additional data inserted into them. These are the following:

**id: import_kt_address_info**

$$ will be replaced with the number of kt addresses that have been found

**id: transaction_confirm_info**

The first $$ will be replaced with the amount of the transaction

The second $$ will be replaced with the destination address of the transaction

## Paid Translations

We are currently looking to pay for full translations - please send a message to @TezBox_Wallet on Twitter with the language and the cost in USD to create a new translation

## Credits

Thanks to all of the following contributons who have helped to provide various translations for TezBox!

* Russian - Uladzimir Bialko and @bvabonda (provided for free)
* German - @whaleHunterBiz (provided for free)
* Turkish - @dorukbaggins, reviewed by @oliversimon (provided for free)
* Chinease - @catsigma (provided for free)
* Spanish - @Dlanzag (provided for free)
* Brazilian Portugese - Luiz Milfont  @luizmilfont (provided for free)
* Romanian - ₳ndrei Cristian @kimorq94
* Korean - @SnowCareBeauty
* Slovak - Daniel Mitera @DanielMitera
* Japanese - @xujiachen89
