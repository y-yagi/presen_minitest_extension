## [minitest-retry](https://rubygems.org/gems/minitest-retry)

* テストが失敗した際に、自動的にテストを再実行する
* inspired by [rspec-retry](https://github.com/NoRedInk/rspec-retry)
  * ~~ぱくり~~

```ruby
$ ./bin/rake test
[MiniestRetry] retry 'test_fail' count: 1,  msg: test fail
[MiniestRetry] retry 'test_fail' count: 2,  msg: test fail
[MiniestRetry] retry 'test_fail' count: 3,  msg: test fail
F

Finished in 0.002479s, 403.4698 runs/s, 403.4698 assertions/s.

  1) Failure:
Minitest::RetryTest#test_fail [test/minitest/sample_test.rb:6]:
test fail
```
