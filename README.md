# LMP 足りないピース LP

LIFE MAKE PARTNERS（LMP）のパズル型ランディングページ。
6つのピース（営業／法人開拓／顧客育成／商談／管理／収益）がスクロールで1つの塊になり、簡易診断・LINE診断へつなぐ。

## 公開先

```
https://nrealize6078-hue.github.io/lmp-puzzle-lp/
```

| | |
|---|---|
| リポジトリ | `nrealize6078-hue/lmp-puzzle-lp`（public） |
| 作業コピー（編集元） | `Documents/Claude/LMP_パズルLP/index.html` |
| 公開方法 | GitHub Pages（main / ルート） |
| 検索掲載 | **しない**（noindex。仮公開のため） |

## 更新手順

1. 編集元 `LMP_パズルLP/index.html` を直す（このリポジトリの `index.html` は直接触らない）
2. `python build.py` で `_公開用/` に組み直す
3. `_公開用/` で commit → push

## 注意

- LINE導線はすべて `https://lin.ee/ZbhfV7X`。LINE公式の友だち追加画像が読めない環境では同じリンク先の緑ボタンに切り替わる
- 申込フォームは送信先未接続（送信すると「連携未設定」の表示が出るだけ）
