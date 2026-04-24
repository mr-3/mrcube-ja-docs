インストール
================

.. contents:: コンテンツ 
   :depth: 2


動作環境
------------
   
MR\ :sup:`3` \は，Java言語で実装されている．
ver. 26.4.3 では，`Liberica Standard JDK 25 <https://bell-sw.com/pages/downloads/#jdk-25-lts>`_
が組み込まれているため，別途JDKをインストールする必要はない．
Linuxで実行する際には，Java Runtime Environment (JRE) 25以降のインストールが必要である．

動作確認は，以下の環境で行っている．

* MS Windows 11
* macOS Tahoe 26.4

インストール方法
-------------------

Windows
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
#. `Microsoft StoreのMRCubeのページ <https://apps.microsoft.com/detail/9nmgtwtl1fvg?hl=ja-JP&gl=JP>`_  にアクセスし，「Microsoft Store で見る」ボタンをクリックする． 
#. 「インストール」ボタンをクリックする．
#. デスクトップに作成されるショートカットを実行する．

macOS (dmgファイルのダウンロード)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
#. `ダウンロードページ <https://github.com/mr-3/mrcube/releases>`_  から **mrcube-26.4.3.dmg** をダウンロードしてファイルを開く．
#. 「MRCube.app」をApplicationsディレクトリにドラッグアンドドロップし，「MRCube.app」を実行する．
#. 「“MRCube”はインターネットからダウンロードされたアプリケーションです。開いてもよろしいですか?」と表示されるため，「開く」ボタンをクリックする．

macOS (Homebrew)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
#. `Homebrew <https://brew.sh/>`_ をインストールする．
#. ターミナル.appから ``brew tap mr-3/tap`` と ``brew install --cask mrcube`` を実行する．
#. Applicationsディレクトリの中の「MRCube.app」を実行する．
#. 「“MRCube”はインターネットからダウンロードされたアプリケーションです。開いてもよろしいですか?」と表示されるため，「開く」ボタンをクリックする．

Linux
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
#. `ダウンロードページ <https://github.com/mr-3/mrcube/releases>`_  から **mrcube-24.4.1-all.jar** をダウンロードする．
#. **java -jar mrcube-26.4.3.jar** を実行する．

Docker
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
#. `Docker Desktop for Mac <https://www.docker.com/products/docker-desktop>`_ をインストール
#. `XQuarts <https://www.xquartz.org/>`_ をインストールして実行し，「設定」メニューの「セキュリティ」タブから「ネットワーク・クライアントからの接続を許可」にチェックを入れる
#. `mrcube-ja.sh <https://raw.githubusercontent.com/mr-3/docker-mrcube/main/mrcube-ja/mrcube-ja.sh>`_ をダウンロード
#. ターミナル.appから./mrcube-ja.sh を実行する
#. ホームディレクトリ直下の「mrcube」ディレクトリからDocker上の「/home/mrcube/mrcube-home」ディレクトリにアクセス可能

アンインストール方法
------------------------

Windows
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
「設定」画面からアプリメニューを選択し，インストールされているアプリ一覧から **MRCube** を選択し，アンインストールする．

macOS
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
「Applications」ディレクトリの中の「MRCube.app」をゴミ箱に移動する．

Linux
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
「mrcube-26.4.3-all.jar」を削除する．

使用しているライブラリ
----------------------
MR\ :sup:`3` \は，以下のライブラリを使用している．

* `FlatLaf - Flat Look and Feel <https://www.formdev.com/flatlaf/>`_ (`License <http://www.apache.org/licenses/LICENSE-2.0>`__)
* `JGraph and JGraphAddons <http://www.jgraph.com/>`_ (`License <https://github.com/jgraph/legacy-jgraph5/blob/master/LICENSE>`__)
* `Apache Jena <https://jena.apache.org/>`_ (`License <http://www.apache.org/licenses/LICENSE-2.0>`__) 
* `Apache Batik SVG Toolkit <https://xmlgraphics.apache.org/batik/>`_ (`License <https://xmlgraphics.apache.org/batik/license.html>`__)
* `Drawing Graphs with VGJ <http://www.eng.auburn.edu/department/cse/research/graph_drawing/graph_drawing.html>`_ (`License <http://www.eng.auburn.edu/department/cse/research/graph_drawing/COPYING>`__)
* `Material Design icons by Google <https://github.com/google/material-design-icons>`_ (`License <https://www.apache.org/licenses/LICENSE-2.0.txt>`__)
