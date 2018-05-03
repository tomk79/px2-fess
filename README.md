broccoli-html-editor/broccoli-module-fess
=========

FESS document modues for broccoli-html-editor.


## Usage - 使い方

### 1. [Pickles 2](http://pickles2.pxt.jp/) をセットアップ

### 2. composer.json に追記

```json
{
    "require": {
        "broccoli-html-editor/broccoli-module-fess": "^0.1"
    }
}
```

### 3. composer を更新

```
$ composer update
```

### 4. px-files/config.php に追加

```php
// config for Pickles2 Desktop Tool.
@$conf->plugins->px2dt->paths_module_template["FESS"] = "./vendor/pickles2/broccoli-module-fess/modules/";
```


## License

MIT License


## Author

- (C)Tomoya Koyanagi <tomk79@gmail.com>
- website: <http://www.pxt.jp/>
- Twitter: @tomk79 <http://twitter.com/tomk79/>
