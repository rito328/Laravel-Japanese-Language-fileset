# Laravel-Japanese-Language-fileset
※下位バージョン（5.6/5.5）の言語ファイルセットはブランチを切り替える事で入手可能です。
## Laravel5.7 日本語言語ファイルセット
1. resources/lang/ja の設置

resources/lang/ja ディレクトリを作成し、その中にこれらのファイルを設置してください。

または、git submoduleとしてご利用して下さい。

```
git submodule add https://github.com/rito-nishino/Laravel5.5-Japanese-Language-fileset.git resources/lang/ja
```

2. config/app.php の locale を ja へ変更する

```
'locale' => 'ja',
```

### OFFICIAL

Ritolabo https://www.ritolab.com/

Laravelインストール後の初期設定と入門
https://www.ritolab.com/entry/48  
Laravelのvalidationメソッドでバリデーションを実装する  
https://www.ritolab.com/entry/40  
Laravelのフォームリクエストクラスでバリデーションロジックをコントローラから分離する  
https://www.ritolab.com/entry/41
