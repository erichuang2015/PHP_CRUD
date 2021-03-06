# PHP_CRUD

### 概要
* PHPに作った簡単な**CRUD(Create, Read, Update, Delete)掲示板**です。

### 開発言語
* **言語** <br>
PHP

* **DB** <br>
MariaDB

* Javascript, HTML, bootstrap

### 機能紹介
#### 会員登録
> 会員登録です。IDとnicknameを入力します。
> IDとnicknameには重複チェック機能があります。

![2](https://user-images.githubusercontent.com/43987455/48406965-1e499d00-e779-11e8-893b-a14ff2af710d.JPG)

> 重複チェックをしなかったら、登録はできません。

![3](https://user-images.githubusercontent.com/43987455/48407616-98c6ec80-e77a-11e8-9332-7075655e1202.JPG)

![4](https://user-images.githubusercontent.com/43987455/48407623-9c5a7380-e77a-11e8-98d4-501cd15785ef.JPG)

#### ログイン
> ログインです。IDがない場合やPasswordが違う場合はログインできません。

![1](https://user-images.githubusercontent.com/43987455/48407976-797c8f00-e77b-11e8-818c-ec546fe59fea.JPG)

![default](https://user-images.githubusercontent.com/43987455/48410033-d595e200-e780-11e8-9647-bf6ef4a834f7.JPG)

#### 掲示板
> 掲示板です。掲示物のno、名前、題目、時間の情報が出ます。題目をクリックしたら、内容を見ることができます。

![1](https://user-images.githubusercontent.com/43987455/48695404-69086080-ec22-11e8-960e-dac2a7138a14.JPG)

> 掲示板はページング機能があります。

![_2_1](https://user-images.githubusercontent.com/43987455/48695517-b2f14680-ec22-11e8-8c98-e468d1be2cbd.jpg)
![_2_2](https://user-images.githubusercontent.com/43987455/48695518-b2f14680-ec22-11e8-9ddb-a967f49396aa.jpg)
![_2_3](https://user-images.githubusercontent.com/43987455/48695515-b258b000-ec22-11e8-9a81-1cae74cc08ed.jpg)

> 題目や内容や名前の一部分で検索可能です。

![11](https://user-images.githubusercontent.com/43987455/48695646-fe0b5980-ec22-11e8-8d50-5523c101e052.jpg)
![22](https://user-images.githubusercontent.com/43987455/48695827-8984ea80-ec23-11e8-8dc8-1afc21a92267.JPG)

> 掲示板上にはログインした人のnicknameが出ます。

![5](https://user-images.githubusercontent.com/43987455/48408272-4b4b7f00-e77c-11e8-8c47-a104f195b5d4.JPG)

> アップロードの時、名前は自動的にnicknameになります。

![6](https://user-images.githubusercontent.com/43987455/48408398-94033800-e77c-11e8-8263-8879fb9407c5.JPG)

> 自分の掲示物だけを修正/削除することが可能です。

![7](https://user-images.githubusercontent.com/43987455/48409096-52738c80-e77e-11e8-92ae-4e76a8da265b.JPG)

![8](https://user-images.githubusercontent.com/43987455/48409097-52738c80-e77e-11e8-83a7-55b5ce2355b6.JPG)

> 管理者(admin)の場合は全掲示物を修正/削除することが可能です。

![9](https://user-images.githubusercontent.com/43987455/48409293-c3b33f80-e77e-11e8-8e1e-5b0a2baa39a5.JPG)

#### ログアウト
> ログアウトをクリックすると、ログイン画面に戻ります。

