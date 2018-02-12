# gogsBase16
Base16 stylish theme for gogs

![gogsBase16 preview image](assets/preview.png)

This stylish theme is based on [base16 tomorrow night by chriskempson](https://github.com/chriskempson/base16).

## Getting Started

There are 2 ways of installing this theme. One is server sided, the other client sided.

## Installing

### Server sided

Gogs has an official way of loading custom css. You can find the doc [here](https://gogs.io/docs/features/custome_template).

* Create a file named custom.css under public/css directory.
* Paste the content of [gogsBase16.css](gogsBase16.css).

It seems the offical doc has a wrong url for the next step. My ```head.tmpl``` was located in ```/templates/inject/head.tmpl```

* Edit file ```custom/templates/inject/head.tmpl``` and add a line ```<link rel="stylesheet" href="/css/custom.css">```
* Restart Gogs

### Client sided
* You need to have the stylish extension installed in your browser. Get the firefox extension [here](https://addons.mozilla.org/de/firefox/addon/stylish/) and the chrome one [here](https://chrome.google.com/webstore/detail/stylish-custom-themes-for/fjnbnpbmkenffdnngjfgmeleoegfcffe).
* Install [this style](https://userstyles.org/styles/155619/gogsbase16) and change the URL to take effect.


## Contributing
Feel free submit pull requests, as I'm not a web developer at all.

Please stick to the base16 tomorrow night color scheme. Any help is welcome.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details.
