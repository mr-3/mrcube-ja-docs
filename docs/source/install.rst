インストール
================

.. contents:: コンテンツ 
   :depth: 2


動作環境
------------
   
MR\ :sup:`3` \は，Java言語で実装されている．実行するには，JRE (Java Runtime Environment) 17または，それ以上が必要である．
ver. 24.5.1 では，JRE21が組み込まれているため，別途JREをインストールする必要はない．

動作確認は，以下の環境で行っている．

* MS Windows 11 + OpenJDK version "21.0.3"

インストール方法
-------------------

Windows
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
#. `ダウンロードページ <https://github.com/mr-3/mrcube/releases>`_  から **mrcube-24.5.1.msi** をダウンロードしてファイルを開く．
#. 「WindowsによってPCが保護されました」と表示されるため，「詳細情報」リンクをクリックする．
#. 「実行」ボタンをクリックする．
#. 「この不明な発行元からのアプリがデバイスに変更を加えることを許可しますか？」というダイアログが表示されるため，「はい」をクリックする．
#. デスクトップに作成されるショートカットを実行する．

macOS
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
#. `Docker Desktop for Mac <https://www.docker.com/products/docker-desktop>`_ をインストール
#. `XQuarts <https://www.xquartz.org/>`_ をインストールして実行し，「設定」メニューの「セキュリティ」タブから「ネットワーク・クライアントからの接続を許可」にチェックを入れる
#. `mrcube-ja.sh <https://raw.githubusercontent.com/mr-3/docker-mrcube/main/mrcube-ja/mrcube-ja.sh>`_ をダウンロード
#. ターミナル.appから./mrcube-ja.sh を実行する
#. ホームディレクトリ直下の「mrcube」ディレクトリからDocker上の「/home/mrcube/mrcube-home」ディレクトリにアクセス可能

Linux
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
#. `ダウンロードページ <https://github.com/mr-3/mrcube/releases>`_  から **mrcube-24.5.1-all.jar** をダウンロードする．
#. **java -jar mrcube-24.5.1.jar** を実行する．

アンインストール方法
------------------------

Windows
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
「設定」画面からアプリメニューを選択し，インストールされているアプリ一覧から **mrcube-24.5.1** を選択し，アンインストールする．

使用しているライブラリ
----------------------
MR\ :sup:`3` \は，以下のライブラリを使用している．

* `FlatLaf - Flat Look and Feel <https://www.formdev.com/flatlaf/>`_ (`License <http://www.apache.org/licenses/LICENSE-2.0>`__)
* `JGraph and JGraphAddons <http://www.jgraph.com/>`_ (`License <https://github.com/jgraph/legacy-jgraph5/blob/master/LICENSE>`__)
* `Apache Jena <https://jena.apache.org/>`_ (`License <http://www.apache.org/licenses/LICENSE-2.0>`__) 
* `Apache Batik SVG Toolkit <https://xmlgraphics.apache.org/batik/>`_ (`License <https://xmlgraphics.apache.org/batik/license.html>`__)
* `Drawing Graphs with VGJ <http://www.eng.auburn.edu/department/cse/research/graph_drawing/graph_drawing.html>`_ (`License <http://www.eng.auburn.edu/department/cse/research/graph_drawing/COPYING>`__)
* `Material Design icons by Google <https://github.com/google/material-design-icons>`_ (`License <https://www.apache.org/licenses/LICENSE-2.0.txt>`__)