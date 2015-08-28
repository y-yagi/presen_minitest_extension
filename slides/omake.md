## おまけ

* Rails 5から入る`rails test`というテストの仕組みもminitestのextensionの機構を使用している
* この辺りのコード参照
  * [rails/minitest_plugin.rb](https://github.com/rails/rails/blob/master/railties/lib/rails/test_unit/minitest_plugin.rb)
  * [rails/reporter.rb](https://github.com/rails/rails/blob/master/railties/lib/rails/test_unit/reporter.rb)
* Railsはminitestと共に歩む
