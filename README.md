# Claude Code ワークスペース デモ

AI木曜会 Claude Code ハンズオン（3/11・3/16）で使うデモリポジトリです。

## このリポジトリでできること

- Claude Code を IDE のターミナルで動かす
- 用途別のフォルダ構成を体験する
- スキル（スラッシュコマンド）を作って実行する

---

## セットアップ

### 1. このリポジトリをクローン

```bash
git clone https://github.com/Akane2block/claude-code-workspace-demo.git
cd claude-code-workspace-demo
```

または ZIP でダウンロードして解凍してもOK。

### 2. IDE でフォルダを開く

VSCode / Antigravity / Cursor のいずれかで、このフォルダを開く。

### 3. ターミナルを開いて Claude Code を起動

```
claude
```

---

## フォルダ構成

```
claude-code-workspace-demo/
├── 日記/               ← 日々の記録
├── 仕事/
│   ├── 日報/
│   │   ├── output/    ← 生成された日報の保存先
│   │   └── 日報テンプレート.md
│   └── 議事録/
├── パーソナル/          ← 個人メモ・タスクなど
├── .claude/
│   └── skills/        ← スキル（スラッシュコマンド）置き場
│       └── daily-report.md
└── CLAUDE.md           ← Claude Code へのルール設定
```

---

## スキルを使ってみる

Claude Code のターミナルで以下を入力：

```
/daily-report
```

→ `仕事/日報/output/` に今日の日報が自動生成されます。

---

## スキルをカスタマイズする

`.claude/skills/daily-report.md` を開いて、自分の使い方に合わせて書き換えてください。

プログラミング不要。日本語で書くだけでOKです。

---

## 参考リンク

- [Claude Code 公式ドキュメント](https://docs.anthropic.com/ja/docs/claude-code/overview)
- [VSCode](https://code.visualstudio.com/)
- [Antigravity](https://antigravity.google/)
- [Cursor](https://www.cursor.com/)
