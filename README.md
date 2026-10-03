# kzhrknt / claude-plugins

**kzhrknt の Claude Code プラグイン棚（マーケットプレイス）。**
棚の登録は一度だけ。あとは欲しいプラグインを install するだけで、以後の新作もこの棚に並びます。

## 棚の登録

```
/plugin marketplace add kzhrknt/claude-plugins
```

## プラグイン一覧

| プラグイン | 説明 | インストール |
|---|---|---|
| [add-ja-subs](https://github.com/kzhrknt/add-ja-subs) | 英語動画に日本語字幕を焼き込む全ローカルAIパイプライン（Whisper + エージェント翻訳 + ffmpeg、課金なし） | `/plugin install add-ja-subs@kzhrknt` |
| [mov-to-conte](https://github.com/kzhrknt/mov-to-conte) | 動画（ローカル / YouTube等のURL）から16:9の絵コンテ PDF・PPTX を起こす。カット検出＋ローカルWhisper＋エージェント注釈、課金なし | `/plugin install mov-to-conte@kzhrknt` |
| [humanize-ja](https://github.com/kzhrknt/humanize-ja) | AIが書いた日本語から、AI特有の癖を抜いて人の文章に戻す。提案書・企画書・技術文書・記事に（原文にない数値や主語は足さない） | `/plugin install humanize-ja@kzhrknt` |

## 更新

```
/plugin marketplace update kzhrknt
```

各プラグインの詳細・必要環境・権利上の注意は、それぞれのリポジトリのREADMEを参照してください。
