📄 PDF質問応答AIシステム
これは、LangChain + OpenAI + FAISS を活用して、任意の PDF に関する質問に自然言語で答えてくれる AI アシスタントです。

✅ 機能概要
任意の PDF ファイルを読み込み

テキストを分割し、ベクトル化して FAISS インデックスを作成

GPT-3.5/4 を使って関連情報をもとに質問に回答

🧠 使用技術
Python 3.x

LangChain

OpenAI GPT API

FAISS（類似文書検索）

PyPDF2（PDFテキスト抽出）

dotenv（APIキー管理）

🛠 セットアップ手順
.env ファイルを作成し、以下を記述：

env
コピーする
編集する
OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
必要なライブラリをインストール：

bash
コピーする
編集する
pip install -r requirements.txt
PDF をベクトル化：

bash
コピーする
編集する
python pdf_qa_setup.py
質問を実行：

bash
コピーする
編集する
python pdf_qa.py
🖼 実行例（スクリーンショット）
📘 インデックス作成の様子：

🤖 質問＆回答の様子：

🗂 ディレクトリ構成（例）
pgsql
コピーする
編集する
pdf-qa-system/
├── pdf_qa.py
├── pdf_qa_setup.py
├── samplePDF.pdf
├── index.faiss/
├── .env
├── .gitignore
├── README.md
└── requirements.txt
🙋‍♀️ 開発者
Riho Kamada（@riho_dev）
