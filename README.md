# Bookmeter_LoadBookList

## 説明

このPythonコードは、[読書メーター](https://bookmeter.com)に登録されている積読本、または読んだ本をcsvとして出力することができるプログラムです。

## 使い方

以下の手順で設定を行ってください：

1. **Seleniumをインストール**  
   `pip install selenium`を実行し、Seleniumをインストールします。  
   まだインストールしていない場合は、これを実行してダウンロードしてください。

2. **スクリプトの選択**  
   - 読んだ本のデータを取得したい場合は、`Bookmeter_ReadBookList.py`を使用します。
   - 積読本のデータを取得したい場合は、`Bookmeter_LoadBookList.py`を使用します。

3. **URLの変更**  
   スクリプト内のURLが現在、自分のアカウント（白深やよい）のURLに設定されていますが、これを以下のように変更する必要があります：
   - 読んだ本の場合は、自分のアカウントの読んだ本のURLに変更します。
   - 積読本の場合は、自分のアカウントの積読本のURLに変更します。

   例:  
   `https://bookmeter.com/users/1291485/books/stacked` の部分を、自分のアカウントのページURLに書き換えます。

4. **ページのURLを変更**  
   ページ遷移を処理する部分のURLも変更する必要があります：
   - `https://bookmeter.com/users/1291485/books/stacked?page={i}` の部分を、自分のURLに置き換えます。
   - `?page={i}` の前の部分を、自分のアカウントのURLに対応するように変更します。

5. **スクリプトの実行**  
   以上の変更が完了したら、スクリプトを実行してください。

何かわからないことがあったら、TwitterのDM,またはメンションをしてください。  
[@shirafuka_yayoi](https://x.com/shirafuka_yayoi)