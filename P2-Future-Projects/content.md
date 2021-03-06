---
title: "将来のプロジェクト"
slug: future-projects
---

プロジェクトにもっと変更を加えると、_GitHub Desktop_ は _Uncommited Changes_ というラベルを表示します。次にどのファイルをステージする（含める）か選択肢、これらのファイルをコミットし、そのコミットをGitHubへプッシュ（同期）することができます。

これでGitの使い方の最も基本的なことがわかりましたね。この強力なツールにはまだまだたくさん機能がありますが、このチュートリアルでは紹介しません。今のところは、作業中にあなたのプロジェクトへ変更をコミットし、プッシュする過程に慣れてもらいたいのです。

## 履歴と冗長性

このプロセスは超重要なものです。履歴と冗長化の両方を与えてくれるからです。各コミットは別々に保存され、変更した箇所を説明する特定のメッセージが添えられます。各コミットを参照すれば、何が変更されたのかがわかります。最近追加したコードから発生した新しいバグのデバッグをしようとするような場合には、何時間も時間を節約できるでしょう。

冗長化もできます。あなたのコンピュータに何かが起こっても（ハードドライブが故障する、なくなる、盗まれるなど）、GitHugにコピーがあります！ これはもちろん、あなたが自分のコードを*プッシュ*した場合ですが。ですから、頻繁にコミットして、常にプッシュすることをお忘れなく！ 「プッシュしておいて良かった」と感激しますよ:)

![ms-video](https://s3.amazonaws.com/mgwu-misc/GitHubDesktop/history.mp4)

# あなたの責任

新たなプロジェクトを開始するたびに、まずは新しいGitレポジトリを作成するべきです。やり方を忘れたら、いつでも前のページを参照できます。

> [action]
> あなたの責任は次の通りです。
>
1. 各プロジェクトの開始時にレポジトリを作成すること
2. **各チュートリアルページ** の最後に、変更されたファイルをコミットし、かつプッシュすること

<!--  -->

> [info]
> 説明を含んだコミットメッセージを使うようにしてください！ 「このコミットは \_\_\_\_\_\_\_\_する」という形で、空白部分を常に記入すべきです。コミットに README が追加される場合、コミットメッセージは「READMEを追加する」とすべきです。位置関係の機能を新しく実装するのであれば、コミットのメッセージは「ロケーションモニタリングを実装する」とします。Facebookアカウントを使ったユーザーサインアップのバグを修正するのであれば、コミットのメッセージは「Facebookアカウントのサインアップのバグを修正する」とします。

こうすることで優れた習慣を身に付ける役に立ちます。自分のアプリやゲームに取り掛かるときに、Gitを使い続けて、変更を追跡し、プロジェクトのバックアップができるようになります。自分のプロジェクトを始めたら、小さな機能を完成させるたびにコミットし、プッシュすることになります。少なくとも一日に一度はコミットし、プッシュすることが重要です。優れた開発者はたいてい一日に何度もコミットし、プッシュしています。
