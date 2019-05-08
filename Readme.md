# Laramoud Installer
An Installer for laramoud module

# Install
```
composer require --dev laramoud/installer:dev-master
```

or add in your composer.json
```
"require-dev": {
    "laramoud/installer": "^1.0"
},
```
the default dir installed module is modules/ if you want custom path add some extra configuration in your composr.json file
```
"extra": {
    "laramoud": {
            "module_path": "custom_dir/"
    }
},
```
