## [minitest-sound](https://rubygems.org/gems/minitest-sound)

* テスト実行中/テスト成功時/テスト失敗時 それぞれのタイミングで曲を再生する
  * それだけ

```ruby
require 'minitest/sound'

Minitest::Sound.success = '/aaa/bbb/xxx.mp3' # Sound file which does play when a test succeeded.
Minitest::Sound.failure = '/aaa/bbb/xxx.mp3' # Sound file which does play when a test failed.
Minitest::Sound.during_test = '/aaa/bbb/xxx.mp3' # Sound file which does play during test.

```

* テスト中にゲームのバトルのBGMとかかけるとテンション上がって良いですよ
