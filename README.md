# BlazorApp

Azure OpenAIのChatGPT APIを使用して、Azure Cognitive Searchのコンテンツを分析するソースコードをGPT-4でほぼ自動作成しました。
構築方法は下記を参照して下さい。
[Azure OpenAIのChatGPT APIとGPT-４を利用してFAQチャットボットを作成できた](https://blog.jbs.co.jp/entry/2023/04/05/130703)

>GPT-4で生成したコードはとりあえず動く程度の内容です。サンプルデータ以外ではエラーが発生する可能性があります。
>Azure OpenAI APIの使用料金に注意してください。

検証には下記のデータを使用しました。
[自治体における「子育てAIチャットボット」の普及に向けたオープンデータ化についての「報告書」及び「FAQデータセット」を公開 | LINE Corporation | CSR活動レポート](https://linecorp.com/ja/csr/newslist/ja/2020/260)
Azure Cognitive Searchで作成したサンプルデータの内容
![Azure Cognitive Searchで作成したサンプルデータ](https://cdn-ak.f.st-hatena.com/images/fotolife/j/jbs_mkabuki/20230329/20230329165058.png)

Azure OpenAI APIのエンドポイントとAPIキーを設定して下さい。
![Azure OpenAI APIのエンドポイントとAPIキー](https://github.com/mkabuki/BlazorApp/blob/master/image/CallOpenAIAPI%E3%81%AE%E8%A8%AD%E5%AE%9A.png?raw=true)

Azure Cognitive Searchのエンドポイントとインデックス名、APIキーを設定して下さい。
![Azure Cognitive Searchのエンドポイントとインデックス名とAPIキー](https://github.com/mkabuki/BlazorApp/blob/master/image/ExecuteSearch%E3%81%AE%E8%A8%AD%E5%AE%9A.png?raw=true)



