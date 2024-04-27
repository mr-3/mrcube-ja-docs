インストール
================

.. contents:: コンテンツ 
   :depth: 2


動作環境
------------
   
MR\ :sup:`3` \は，Java言語で実装されています．実行するには，JRE (Java Runtime Environment) 18または，それ以上が必要です．
ver. 22.5.2 では，JRE18が組み込まれているため，別途JREをインストールする必要はありません．

動作確認は，以下の環境で行っています．

* MS Windows 111 + openjdk version "18.0.1.1"
* Mac OS 14.4.1 + openjdk version "18.0.1.1"

インストール方法
-------------------

Windows
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
#. `ダウンロードページ <https://github.com/mr-3/mrcube/releases>`_  から**mrcube-22.5.2.msi**をダウンロードしてファイルを開く．
#. 「WindowsによってPCが保護されました」と表示されるため，「詳細情報」リンクをクリックする．
#. 「実行」ボタンをクリックする．
#. 「この不明な発行元からのアプリがデバイスに変更を加えることを許可しますか？」というダイアログが表示されるため，「はい」をクリックする．
#. デスクトップに作成されるショートカットを実行する．

macOS
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
#. `ダウンロードページ <https://github.com/mr-3/mrcube/releases>`_  から**mrcube-22.5.2-x64.dmg**をダウンロードして展開し，「アプリケーション」フォルダに「mrcube-22.5.2.app」をコピーする．
#. **mrcube-22.5.2.app**を実行する．
#.「"mrcube-22.5.2"はインターネットからダウンロードされたアプリケーションです。開いてもよろしいですか？」というダイアログが表示されるため、「開く」ボタンをクリックする．

アンインストール方法
------------------------

Windows
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
「設定」画面からアプリメニューを選択し，インストールされているアプリ一覧から**mrcube-22.5.2**を選択し，アンインストールする．

macOS
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
アプリケーションフォルダから**mrcube-22.5.2.app**を削除する．

使用しているライブラリ
----------------------
MR\ :sup:`3` \は，以下のライブラリを使用しています．

* `FlatLaf - Flat Look and Feel <https://www.formdev.com/flatlaf/>`_ (`License <http://www.apache.org/licenses/LICENSE-2.0>`_)
* `JGraph and JGraphAddons <http://www.jgraph.com/>`_ (`License <https://github.com/jgraph/legacy-jgraph5/blob/master/LICENSE>`_)
* `Apache Jena <https://jena.apache.org/>`_ (`License <http://www.apache.org/licenses/LICENSE-2.0>`_) 
* `Apache Batik SVG Toolkit <https://xmlgraphics.apache.org/batik/>`_ (`License <https://xmlgraphics.apache.org/batik/license.html>`_)
* `Drawing Graphs with VGJ <http://www.eng.auburn.edu/department/cse/research/graph_drawing/graph_drawing.html>`_ (`License <http://www.eng.auburn.edu/department/cse/research/graph_drawing/COPYING>`_)
* `Material Design icons by Google <https://github.com/google/material-design-icons>`_ (`License <https://www.apache.org/licenses/LICENSE-2.0.txt>`_)