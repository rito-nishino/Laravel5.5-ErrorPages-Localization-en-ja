# Laravel5.5-ErrorPages-Localization-en-ja
Laravel5.5 エラーページ 多言語化対応[英語/日本語] ファイルセット

## 設定ファイル
config/app.php  
追加項目のみの収録となります。  
このファイルについては記載項目をお持ちのapp.phpに追加してください。

## エラーページ確認用ルーティング
laravel/routes/web.php

## HTTPステータスコード別　エラーページ用　言語ファイル
### 英語
resources/lang/en/http_status_code.php
### 日本語
resources/lang/ja/http_status_code.php

## 独自エラーページ　レイアウトファイル
resources/views/errors/layouts/base.blade.php

## 多言語化対応　独自エラーページ
resources/views/errors/400.blade.php  
resources/views/errors/401.blade.php  
resources/views/errors/403.blade.php  
resources/views/errors/404.blade.php  
resources/views/errors/500.blade.php  
resources/views/errors/503.blade.php  
