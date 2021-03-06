# READ ME

Scala-Playframeworkの学習をするためのハンズオン資料です

## requirements

### lesson1

- sbt1.3.x

### lesson2

- Docker

## versions

- Playframework 2.8.x
- MySQL 5.7.x
- Slick 3.3.x

## Directory

```sh
├── README.md
├── lesson1
│   ├── documents
│   ├── example
│   └── handson
└── lesson2
    ├── documents
    ├── example
    └── handson
```

- documents
  - handson documents.(markdown file)
- example
  - Source code when all hands-on is completed.
- handson
  - handson folder.

## License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/"><img alt="クリエイティブ・コモンズ・ライセンス" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/3.0/88x31.png" /></a><br />この 作品 は <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/">クリエイティブ・コモンズ 表示 - 非営利 - 継承 3.0 非移植 ライセンス</a>の下に提供されています。


# etc

## TODO/悩み

1. 外部キー制約やjoin
1. DBのTimezone設定を日本時間に変更
1. application.confのmysql接続情報は何を参照すればいいのか、後学のためにリンクなりを貼っておく
1. sbtのtask設定を理解して説明を追加する
1. slick codegenで日付関係対応
1. mysqlの日付系のimplicit実装
1. mysqlのtimestamp, datetimeどちらを使うべきか


## memo

1. evolutionsでtweet table作成
1. evolutionsでseed dataを投入
1. slick-codegenでtweetモデル作成
1. tweet一覧表示機能を作成
