## [minitest-slow_test](https://rubygems.org/gems/minitest-slow_test)

* テスト完了時に、一定以上時間のかかったテストの一覧を表示する

```ruby
$ ./bin/rake test
Run options: --seed 4004

# Running:

........................

Finished in 3.367417s, 7.1271 runs/s, 16.0360 assertions/s.

24 runs, 54 assertions, 0 failures, 0 errors, 0 skips
[SlowTest]PageIntegrationTest#test_create_new_page : 1.17s
[SlowTest]PageTest#test_do_not_find_page_when_use_invalid_title : 1.00s
```
