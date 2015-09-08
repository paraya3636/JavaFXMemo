# This is JavaFX memo random

## 環境
- JavaFX + Intellij IDEA
- ライブラリの追加の仕方が分からん。今のとこProjectStructureから突っ込んでる。
- Gradle使いたい

## Hello JavaFX
- JavaFXPlugin入れる
- ウィザードからProject作成
- ビルドして実行

## JavaFXの要素
- Applicationを継承したMainクラス
- Mainクラスから実行される
- とりあえずSuperクラスを見れば大体書いてた

## ApplicationClassの要素
- main()
  Javaのmain()。ApplicationClassに実装させるより別クラスで隠蔽したい…

- start()
  実装必須。アプリが起動する際の入り口となる。
  JavaFX Application Threadで動く。

- init()
  start()の前に呼ばれる。
  JavaFX Application Threadではない。
  SceneまたはStageを生成してはいけない。
  他のJavaFX ObjectはOK。

- stop()
  Applicationが停止する際に呼ばれる。
  JavaFX Application Threadで動く。

## JavaFX Application Threadとは
-

## Applicationを構成する要素

### Stage
- ウインドウ
- StageはSceneを持つ

### Scene
- 画面の枠組み
- Sceneは1つのPaneを持つ

### Pane
- 画面
- Paneの中にViewコンポーネントを組み込む

## Controller生成されてるけど何をコントロールするの？

## ログ
