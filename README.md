# 📄 PDF QA Assistant 🤖📚

**PDF QA Assistant** は、任意のPDFファイルを読み込み、自然言語での質問に答えるAIアシスタントです。LangChain・OpenAI・FAISS を活用し、PDFの内容を理解して回答を生成します。

---

## ✨ 主な機能

- 📄 PDFからテキストを抽出し、意味単位に分割
- 🧠 FAISS でベクトル検索し、関連情報を抽出
- 💬 OpenAI GPT API を使って質問に対する自然な応答を生成

---

## 🔧 技術スタック

- Python 3.x
- [LangChain](https://www.langchain.com/)
- OpenAI GPT-3.5 / GPT-4 API
- FAISS（類似文書検索）
- PyPDF2（PDFテキスト抽出）
- python-dotenv（APIキー管理）

---

## 🛠 セットアップ手順

# .env ファイルに以下を記述（自分の OpenAI API キーに置き換えてください）
OPENAI_API_KEY=sk-あなたのOpenAIキー

📌 今後の機能追加予定
Streamlit UIによるWebインターフェース化

質問履歴の保存・可視化

複数PDFの横断検索対応

👩‍💻 作者
Riho Kamada（@riho_dev）
AI×日常業務効率化をテーマに活動中。
お気軽にフォロー・コラボください！

📜 ライセンス
MIT License
