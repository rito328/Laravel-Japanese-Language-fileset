# Laravel5.5-Japanese-Language-fileset
5.6と5.5の言語ファイルセットは同じ構成なので、両バージョンで使えます。
## Laravel5.6/5.5 日本語言語ファイルセット
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

Laravelのvalidationメソッドでバリデーションを実装する  
https://www.ritolab.com/entry/40  
Laravelのフォームリクエストクラスでバリデーションロジックをコントローラから分離する  
https://www.ritolab.com/entry/41
