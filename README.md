＃参考教材
＊書籍名『できるイラストで学ぶ　プログラミング１年目からのPython』
＊著者/出版社（または発行元）：齋藤大輔、坂本一憲＆できるシリーズ編集部/株式会社インプレス
＊学習の目的：授業の一環としてPythonを学び、Gemini　APIを活用したアプリの開発方法や基礎技術を用いた応用技術を習得するため。

＃Google Gimini API 名刺自動抽出アプリ
参考教材を基にGoogle Gemini API（LiteLLM）を活用し、名刺画像から必要な情報を抽出して構造化するPython　アプリケーションです。参考教材通りの設計にとどまらず、実務で使うことを想定した業務効率化（DX）を見据えて機能拡張と設計を行っています。
ーーーーーーーーーー
工夫した部分（オリジナリティ）
＃１.実務に即した抽出項目の追加
参考教材の基本実装（会社名,名前）に加えて、実際のビジネス現場で必要な＊＊役職・メールアドレス・電話番号・住所・フリガナ＊＊といった詳細項目を実装しました。
＃２.
＃３.

＊01_...ipynb：Gemini API との疎通・基本動作検証
＊02_...ipynb：名刺データ構造のモジュール化（'BusinessCard'クラス）
＊03_...ipynb：画像読み込み・LiteLLM実行・結果出力を行うメインプログラム
ーーーーーーーーーー
＃使用技術
＊Language：Python 3.x
＊AI Model：Google Gemini API（'gemini-3.6-flash' via LiteLLM）
＊Enviroment：Google Colab
＊Version Control：Git/GitHub
＊Development Assistant：Gemini（設計構想・コードレビュー・ロジックのロバスト化に関する相談相手として活用）
ーーーーーーーーーーー
＃今後の展望
