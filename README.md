２つ起動する
・rails
react-railsapiをカレントディレクトリにして「rails s -p 3001」
・react
/react-railsapi/crud_frontをカレントディレクトリにして「npm start」

もしうまく動かなければ「https://qiita.com/yoshimo123/items/9aa8dae1d40d523d7e5d#%E3%81%BE%E3%81%A8%E3%82%81」を参考にライブラリをインストール

詰まったところ
・railsのproducts_contoroller.rbでupdate_attributesがうまく動かない。updateにすればいける。　rails6.1から使えなくなったから。
・reactファイルでエラー
https://github.com/yoshimoto8/React_CRUDを参考に貼り付けたらいけた