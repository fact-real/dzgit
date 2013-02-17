# dzgit

黒い画面をデザイナが使えるようにしてみました。

## 使い方
目的のコマンドを選択して、右クリックでコマンドラインに貼り付けてください。

* 新しい作業用ブランチの作成
```
dzgit [チケットの番号]_[チケットの意味]
例) dzgit 1111_fix_profile_photo
```

* リリース用ブランチの作成
```
dzgit release [生成元ブランチ名] [生成ブランチ名]
例) dzgit release master 20120412_profile_photo
```

* ブランチのマージ
```
dzgit merge [マージ先ブランチ名] [マージしたいブランチ名]
例) dzgit merge release/20120410_bugfixes feature/ticket-1111_fix_profile_photo
```

* 新しいブランチのチェックアウト
```
dzgit checkout [ブランチ名]
例) dzgit checkout feature/ticket-15253_video
```
