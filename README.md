# Chat GPT - Open AI - HTML5 Template

## To store your api key

You can use a php file to store your key, so your key will be protected on the server. To use this option, you must set the "use_php_api" field to true in the config.json file. Insert OpenAI key in php/api.php

Note: To use this option you will need a host with PHP 7 or higher

## Home page

![SmartAnimals](img/smartanimals.png 'SmartAnimals')

## Customizing Characters

You can configure the behavior of the characters by opening the config.json file

    name: Name of the character that will appear in the chat
    image: Character image path
    description: Description of the character that appears in the carousel
    welcome_message: Initial message that the character will send when opening the chat
    display_welcome_message: Configures whether the initial message will appear in the chat
    expert: Label that says what the character is expert at
    background_thumb_color: Character thumbnail background color
    training: Says what the character will be like, how he will behave, what tone he will use in his answer, write everything here in first person

## Badwords

In the config.json file you can define if you want to use a filter for badwords.
This filter is great if you want to prevent the user from typing certain words in the chat. (In config.json: "filter_badwords": true)
You can change list of badwords in json/badwords.json file.

# Contribution

If you want to contribute, feel free to open pull request and push changes. All changes is going through review process.

# Contact

Please send private message if you would need help or want to ask for feature requests

<br>Website: https://unelmaplatforms.com
<br>Facebook: https://www.facebook.com/unelmaplatforms
<br>Twitter: https://twitter.com/unelmaplatforms
