### reporter

* Minitestではテスト結果を表示するのにreporterというクラスを使用している
* テスト実行時に何か処理を行いたい場合独自のreporterクラスを定義して、`self.reporter`に追加すればOK
* reporterで呼び出されるメソッドについては、`AbstractReporter`クラスで定義されている。なので、`AbstractReporter`を継承したクラスを作成し、メソッドをオーバーライドしてあげれば良い。
