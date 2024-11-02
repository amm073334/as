# as
役に立つかもしれないコモンイベント

クレジット表記は不要です。改造・二次配布もご自由に。
- **break**: DERIVE氏が作った「自動改行コモン」を緑帯が出ないように改造したもの。渡された幅を超えないように文字列に改行を入れる。\img・\r・禁則処理にも対応。
- **cmnstack**: コモンセルフでスタックを扱うためのコモンイベント集。再帰処理に便利。
- **pool**: CDBをオブジェクトプールとして管理するコモンイベント集。CDBデータの作成・削除で参照（データ番号や呼び出し変数）を無効化したくない場合に便利。
- **list**:（**pool**に依存）CDBで連結リストを実装するコモンイベント集。一つのCDBタイプで任意の数のリストを作りたい場合や、リストの項目への参照を無効化したくない場合に便利。
- **canvas**: （**pool**に依存）ピクチャ範囲をツリー構造で動的に管理するコモンイベント集。ピクチャの一括移動やZオーダーの自動更新も可。
- **ease**: （**pool**に依存）自流イージングコモン。回転、拡大、不透明度の相対変更にも対応。呼び出し変数を渡せば任意の値をもイージングできる。現在、マップスクロールに対応していない。