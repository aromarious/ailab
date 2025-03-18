# カスタムプロンプトコレクション

## Memory bank

[memory-bank](https://github.com/cline/cline/blob/main/docs/prompting/custom%20instructions%20library/raw-instructions/cline-memory-bank.md)

- タスク（セッション）間を引き継ぐための仕組み
- プロジェクト直下に `memory-bank` を作成し、そこにプロジェクトやタスクの進捗状況の情報をまとめて置いておく

### 使い方

- 初回使用時： 「カスタムプロンプトの指示に従ってください」と指示すると、エージェントがプロジェクトを読んで memory-bank のファイルを作成する
- その後は特に言わなくてもメモリーバンクを読んでタスクをこなしたり更新したりしてくれるが、更新されてないなと思ったら「メモリーバンクを更新してください」と指示するとよい
-
