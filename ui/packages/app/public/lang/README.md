# How to add support for more languages

We would love to support more languages for Gradio 🌎

To add your language, do the following steps:

1. Create a new json file in this directory
2. Name the file after the language code (Here's a list: http://4umi.com/web/html/languagecodes.php)
3. Please provide clear and complete translations. Take a look at the [`en.json`](https://github.com/gradio-app/gradio/blob/master/ui/packages/app/public/lang/en.json) file for the corresponding English text.
4. Lastly, the json file will need to be imported and added into the [`i18n.js` file](https://github.com/gradio-app/gradio/blob/master/ui/packages/app/src/i18n.js)

**Example:** take a look at this [pull request which adds support for Urdu](https://github.com/gradio-app/gradio/pull/621/files)

That's it! 
