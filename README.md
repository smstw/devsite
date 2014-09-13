# SMS 開發用測試網站

將 `composer.json` 放在 /sms 目錄下來統一安裝我們需要的套件

討論位置在此 [sms-uni-dev](https://github.com/smstw/sms-uni-dev)

## 安裝此網站

由於 JConsole 相對於此網站還在測試中，我移除掉 installation 資料夾的存在檢查，每次 clone 回去當作新網站安裝起來即可。

## Composer

``` bash
$ cd ./sms
$ composer update
```

## Joomlatools Composer Installer

我們用 [Joomla Composer](https://github.com/joomlatools/joomla-composer) 套件來做 Ezset 的安裝，詳細設定可以參考 [composer.json](sms/composer.json)

## JConsole

正在嘗試讓 JConsole 可以依靠這個 composer.json 來安裝，但畢竟目錄不同，勢必要更改不少地方，尤其是需要重寫 Install Script
