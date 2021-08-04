# Laravel Desktop

A simple way to deploy a Laravel Web App in a Desktop App

### Installation

```sh
$ git clone https://github.com/BenitoHuertaJr/laravel_desktop.git
$ cd www/application
$ composer install
```
### Configurarion

- 1. Save you application icon inside aasets folder and name it "icon" (the icon extension has to be .ico). 

- 2. In `settings.json`, change you application name
```sh
    "main_window": {
        "title": "Laravel", <-- Your application name
        "icon": "assets/icon.ico",
        "default_size": [1024, 768],
        "minimum_size": [800, 600],
        "maximum_size": [0, 0],
        "disable_maximize_button": false,
        "center_on_screen": true,
        "start_maximized": false,
        "start_fullscreen": false
    },
```
- 3. The run de app.exe

### Compatibility
- PHP 7.4
- Laravel ^7.29

### Credits

- [PHP Desktop](https://github.com/cztomczak/phpdesktop)