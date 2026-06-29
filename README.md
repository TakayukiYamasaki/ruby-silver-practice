# Ruby Silver Practice Questions

Ruby技術者認定試験 Silver レベル向けの **練習問題集**です。

自作の実戦的な練習問題で、Silver認定試験の合格を目指すことができます。

**Ruby 3.1対応版** | 各問題に出題項目を明示 | 詳しい解説付き

---

## 📚 コンテンツ

### 現在公開中

| セット | ファイル | 問題数 | 説明 |
|--------|---------|-------|------|
| **Silver Round 1** | `ruby_silver_round1_practice.md` | 50問 | 基本から応用まで |

### 今後の予定

| セット | 予定時期 | 予定問題数 |
|--------|---------|----------|
| Silver Round 2 | Q2 2026 | 50問 |
| Silver Round 3 | Q3 2026 | 50問 |
| Silver Round 4 | Q4 2026 | 50問 |

---

## ✨ 特徴

✅ **Ruby 3.1対応** - Ruby 3.2で動作確認済み  
✅ **出題項目の明示** - 各問題でカバーしている機能が一目瞭然  
✅ **詳しい解説付き** - 正解と解説で深く理解できる  
✅ **実戦的な問題** - 認定試験の出題傾向に合わせた構成  
✅ **段階的な難易度** - 初級から上級までバランスよく配置

---

## 🎯 カバーしている主要トピック

### データ構造・操作
- **配列操作**: first, last, push, pop, select, compact, uniq, join, slice など
- **ハッシュ操作**: keys, values, delete, clear, has_key? など
- **Range操作**: to_a, count, each, downto, upto など

### 文字列・正規表現
- **文字列操作**: upcase, downcase, reverse, gsub, split, chomp, chop など
- **正規表現**: マッチング、文字クラス、量指定子、パターンマッチング

### 制御フロー・イテレータ
- **イテレータ**: each, select, map, collect, inject, detect など
- **制御構文**: if/unless, case/when, while/until など
- **例外処理**: begin/rescue, raise, カスタム例外

### オブジェクト指向
- **クラス・継承**: super, attr_reader, attr_writer, attr_accessor など
- **クラス変数・インスタンス変数**: @変数, @@変数
- **メソッド**: 定義、呼び出し、可変長引数

### その他
- **数値操作**: even?, odd?, times, %（剰余）など
- **型変換**: to_s, to_i, to_a, to_f など
- **ファイルI/O・ライブラリ**: File.open, gets, readline, read, write など
- **演算・比較**: +, -, *, /, %, **, <=>, && など

---

## 📖 使い方

### 1. ファイルをダウンロード

```bash
git clone https://github.com/yourusername/ruby-silver-practice.git
cd ruby-silver-practice
```

### 2. 問題ファイルを開く

`ruby_silver_round1_practice.md` をエディタで開いてください。

### 3. 進め方

1. **出題項目を確認** - 各問題の冒頭の「【出題項目】」で何を学ぶのかを確認
2. **問題を解く** - 選択肢から正解を選びます
3. **解答を確認** - ファイル下部の「解答と解説」で自分の答えと照合
4. **解説を読む** - Rubyの細かい動作を理解する

---

## 📊 問題セット Round 1 の詳細

### 出題項目分布

- 配列操作: 10問
- 文字列操作: 10問
- イテレータ: 8問
- ハッシュ操作: 5問
- 数値操作: 3問
- 型変換: 3問
- クラス・継承: 3問
- 正規表現: 2問
- IO操作: 2問
- その他（予約語、演算子など）: 5問

### 難易度分布

- 初級: 15問（30%）
- 中級: 28問（56%）
- 上級: 7問（14%）

---

## 🎓 Ruby技術者認定試験について

### Silver試験の概要

| 項目 | 詳細 |
|------|------|
| 試験時間 | 90分 |
| 問題数 | 60問 |
| 問題形式 | 選択問題（1つ選択 / 複数選択混在） |
| 合格ライン | 65%以上の正解 |
| 対象者 | Rubyの基本的な構文を理解し、実務的なコード作成ができるレベル |

詳しくは [Ruby Association 公式サイト](https://www.ruby.or.jp/ja/certification/examination/) を参照してください。

---

## 🚀 効果的な学習方法

### 第1段階: 基礎を学ぶ
- 問題を順番に解く
- 正解/不正解に関わらず必ず解説を読む
- わからない用語は公式ドキュメントで確認

### 第2段階: 弱点を克服
- 間違えた問題を出題項目でグループ化
- 同じ項目の問題を集中的に復習
- 関連メソッドを複数学習

### 第3段階: 実戦練習
- 時間を設定して解く（90分で60問 = 1.5分/問が目安）
- 正解率を記録して進捗を追跡
- 65%以上が安定して取れるまで繰り返す

---

## 🔗 関連リソース

### 公式情報
- [Ruby Association公式サイト](https://www.ruby.or.jp/)
- [Ruby公式ドキュメント](https://docs.ruby-lang.org/ja/)
- [Ruby 3.1 リリースノート](https://www.ruby-lang.org/ja/news/2021/12/25/ruby-3-1-0-released/)

### 学習リソース
- [Ruby入門](https://www.ruby-lang.org/ja/documentation/)
- [RubyDoc.info - Ruby標準ライブラリ](https://ruby-doc.org/)

---

## 📁 ファイル構成

```
ruby-silver-practice/
├── README.md                          # このファイル
├── CHANGELOG.md                       # 更新履歴
├── LICENSE                            # MITライセンス
├── .gitignore
├── EXPANSION_GUIDE.md                 # 拡張ガイド
├── problem_template.md                # 問題テンプレート
├── generate_stats.rb                  # 統計生成スクリプト
└── silver/
    ├── round-1/
    │   ├── ruby_silver_round1_practice.md  (50問)
    │   └── METADATA.md
    └── README_SILVER.md
```

---

## 🤝 貢献について

### 報告・フィードバック

問題の誤りや改善提案がある場合は、以下の方法でお知らせください：

1. **Issues**: バグ報告や機能リクエスト
2. **Pull Requests**: 誤字修正や改善
3. **Discussions**: 一般的な質問や学習について

### 問題追加の基準

新しい問題セットを追加する場合は以下を満たしてください：

✅ Ruby 3.0以降で動作確認済み  
✅ 出題項目が明確に指定されている  
✅ 詳しい解説が付いている  
✅ Silver試験の出題範囲内

詳細は [EXPANSION_GUIDE.md](./EXPANSION_GUIDE.md) を参照してください。

---

## ⚖️ ライセンス

このリポジトリはMITライセンスの下で公開されています。

詳細は [LICENSE](LICENSE) ファイルを参照してください。

---

## 📧 お問い合わせ

質問や改善提案については、GitHubのIssuesで遠慮なくお知らせください。

---

## 🏆 試験合格を応援しています！

このリポジトリで学習して、Ruby技術者認定試験Silver合格を目指してください。

**Happy Learning! 🎉**

---

*最終更新: 2024年*  
*Ruby 3.1+ 対応*
