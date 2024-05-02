# GitManual
WindowsにGitをインストールしてVSCODEでgithubに資料やコードをCommit(アップロード）するまでのチュートリアル

## 本セクションの目的

githubに資料やコードをアップロード(コミット)しておいておくためには、ローカル(任意の手持ちのパソコン)からリモート(github)に変更という流れで作業をする必要がある。そのために必要なプログラムがGitであり、これをインストールすることで、ローカルの変更をリモートに反映させるなどの処理ができるようになる。本セクションでは、これらの処理を行えるようになるまでのセットアップおよび基本操作について解説する。この時、vscodeから直接コミットをはじめgit関連の処理が行えるため、vscodeとgitの組み合わせを前提とする。


# VSCODEのインストール

[VSCODEのインストール方法](https://github.com/SK-Lab-HU/PythonSetupManual)

# Gitのインストール

1. Gitダウンロードページにアクセスする。([Download git](https://git-scm.com/download/win))

2. <b>64-bit Git for Windows Setup</b>を選択する。

![](images/git_downloadpage.png)

3. ダウンロードが完了したら、インストーラーを開く。この時、以下のような画面が出た場合は、Yesを選択する。

![](images/win_conf.png)

4. Installを押す。

![](images/1.png)

5. このあとは、複数回様々なオプションについてダイアログが出てくるが、すべてポジティブなものを選択していく。最終的に以下の画面が表示されれば、Gitのインストールは終了。

![](images/2.png)

6. コマンドプロンプトを開いて、以下コマンドを実行して、gitのバージョンが出てきたらインストールは成功している。

```Bash
git -v
```

![](images/3.png)

