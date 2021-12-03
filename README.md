# git

## Gitのサービス概要
Gitは分散型バージョン管理を実現する`システムの総称`  
簡単に説明すると、ファイルのバージョン管理を簡単に実現するものです。  
システム開発などではファイルを細かく何度も変更するので、それらをバージョン管理して  
「最新のものはどれか」「以前はどのような中身だったか」などの情報を管理できるようにしています。

WordやExcelを上書き保存してしまうと、以前の情報はなくなってしまうが、  
Gitなら使用しているだけで変更履歴が付く⇒情報がなくなってしまう心配がない！

### 参考文献

* Gitとは - IT用語辞典  
https://e-words.jp/w/Git.html

* GitとGitHub、GitLab｜概要・それぞれの違いについて解説！  
https://www.anken-navi.jp/news/work-freelance/git-description/

まずはなんとなくわかればいいです！

# githubとGitLab

**GitHub** と**Gitlab**は、どちらもバージョン管理システムの **Git** を利用して、ソフトウェア開発プロジェクトのソースコード管理を  
共有することができる **Web サービス** のこと。  
細かな違いはあるが、ほぼ同じ機能を有している。  
### 参考文献
* GitとGitHub、GitLab｜概要・それぞれの違いについて解説！  
https://www.anken-navi.jp/news/work-freelance/git-description/

#

<details>
<summary><span style="font-size: 180%"><strong>
1.「GitHub」のアカウントを作成する方法
</strong></span></summary>

- 「GitHub」の公式サイト (https://github.com/) にアクセス   ※写真と全く同じとは限りません

- メールアドレスを入力し「Sign up for GitHub」をクリック（Gmailが望ましい。未所持の場合は[コチラ](https://accounts.google.com/signup/v2/webcreateaccount?continue=https%3A%2F%2Faccounts.google.com%2FManageAccount%3Fnc%3D1&hl=ja&flowName=GlifWebSignIn&flowEntry=SignUp)から無料で登録）

![登録画面](https://user-images.githubusercontent.com/92492715/144171003-19b170aa-0838-41b2-9a75-406c80b5f177.png "登録画面")

- 先ほど入力したアドレスが表示されていることが確認できたら「Continue」をクリック
![](https://user-images.githubusercontent.com/92492715/144172204-75a11062-407a-469e-87ca-e2dd8feb7a8e.png "アドレス確認")

- パスワードを決める　※8文字以上必須
![](https://user-images.githubusercontent.com/92492715/144173474-dd4f804c-366f-49bf-a47c-38502c26d05d.png "パスワード")

- 好きなユーザー名を決めたら「Continue」をクリック
![](https://user-images.githubusercontent.com/92492715/144173989-7f4582aa-8732-46fe-9f07-ea10515d0220.png "ユーザー名")

- 製品のアップデートやお知らせをメールで受け取るか聞かれているので「y」(yes) か「n」(no) 好きなほうを入力後、「Continue」をクリック
![](https://user-images.githubusercontent.com/92492715/144174492-a7d33131-e7c7-44cf-a5b8-86da496027ff.png "メール受け取り")

- 「検証する」をクリックして簡単な質問（〇〇の画像はどれか等）に答える
![](https://user-images.githubusercontent.com/92492715/144175138-ad617066-712c-474d-83a8-e1df63edd31b.png "検証")

- ✅の表示を確認後、「Create account」をクリック
![](https://user-images.githubusercontent.com/92492715/144175466-cd0c63db-f3fc-44eb-bda0-5036d0bc6e9d.png "アカウント作成")

- 登録したアドレスにメールが届くので、記載された８桁の数字を入力する
![](https://user-images.githubusercontent.com/92492715/144177119-e94fb99a-e617-41bf-833f-12335f498c70.png "コード入力")

- 色々聞かれているがとりあえず「Just me」にチェックを入れて下の「Continue」をクリックする
![](https://user-images.githubusercontent.com/92492715/144177506-e8a6f71e-f14d-4cec-b8d5-133b48ca7335.png "いろいろ")

- そのまま「Continue」をクリックする
![](https://user-images.githubusercontent.com/92492715/144177665-70308ad6-b6fb-4b90-9c60-a0afcbc8ac8c.png "そのまま")

- 無償で使えるように「Contunue for free」をクリックする
![](https://user-images.githubusercontent.com/92492715/144177684-59f93577-6f06-4656-ba9d-99630d36fad8.png "無償選択")

- すごいムービーが始まったら成功
![](https://user-images.githubusercontent.com/92492715/144177766-c4803afb-4290-409c-b176-91e810a632ff.png "成功")

</details>

<details>
<summary><span style="font-size: 180%"><strong>
2.「GitLab」のアカウントを作成する方法
</strong></span></summary>

</details>

#

<details>
<summary><span style="font-size: 180%"><strong>
2.GitHubを使う上で知っておきたい事前知識
</strong></span></summary>

</details>

  #

<details>
<summary><span style="font-size: 180%"><strong>
GitHubのリポジトリをGitLabへインポート(コピー)する方法
</strong></span></summary>  
  
 ### 注）大前提としてGitHub,GitLabに登録しているものとする
---

#### 1. gitlabの＋マークから「New Project/repository」を選択する
![](https://user-images.githubusercontent.com/92492715/144364566-98b1f204-1c0c-4dc8-b362-7dafdc678c60.png "新プロジェクト")
---
#### 2. 左下の「import project」を選択する
![](https://user-images.githubusercontent.com/92492715/144364738-4399bbcc-0af9-43c6-9e10-4131db2ea31c.png "")
---
#### 3. どこからインポートするか聞かれているので「GitHub」を選択する
![](https://user-images.githubusercontent.com/92492715/144364877-2279bdaf-258d-45cd-9d13-f8b154247ce3.png "")
---
#### 4. 「Authenticate with GitHub（GitHubで認証する）」を選択する
![](https://user-images.githubusercontent.com/92492715/144365015-a5f34beb-b904-4f6f-a29c-1dbd286824d3.png "")
---
#### 5. パスワードを聞かれたらGitHubのパスワードを入力する
---
#### 6. GitHubのリポジトリへのアクセスを認証すると、インポートできるリポジトリの一覧が表示される。

 すべてのリポジトリを一括でインポートする場合は、「①Import リポジトリの数 repositories」をクリック、特定のリポジトリのみをインポートする場合は、対象リポジトリの「②Import」をクリックする。
![](https://user-images.githubusercontent.com/92492715/144373612-fe8a4938-48cf-4187-a6d3-fbae5fb435df.png "")

①を選択すると注意書きのようなものが表示されるが気にせず「import」
![](https://user-images.githubusercontent.com/92492715/144523316-394360e3-e292-4f8f-88f5-9fc3d7292560.png)

inportを進めると以下のような表示に。

![](https://user-images.githubusercontent.com/92492715/144524122-1c078a7e-aa90-4e73-b290-d46c75c6b089.png)

* 「Complete」・・・import済み
* 「Not started」・・・インポート未実施
* 「Importing...」・・・インポート中
* 「Go to project」・・・インポート済みのリポジトリを開く
  
</details> 

## GitBash

<details>
<summary><span style="font-size: 180%"><strong>
Git Bashとは？
  </strong></span></summary>
  
**GitBash** とはGitの機能が搭載されたBashというもの。  
Bashとは簡単に言えば、命令を画面に打ち込みコンピュータが命令に従いファイルの操作やファイルの編集、削除といった操作ができるソフトウェアです。　　

こんなやつ
![](https://user-images.githubusercontent.com/92492715/144550331-0d52dcd1-ad6c-44a2-a0ed-50872bc7146e.png)
  
</details>
