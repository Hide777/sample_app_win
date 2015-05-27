2014年7月25日版     OS:WndowsXP
2015年5月13日版

# Ruby on Rails チュートリアル：サンプルアプリケーション

これは、以下のためのサンプルアプリケーションです。
[*Ruby on Rails Tutorial: Learn Rails by Example*](http://railstutorial.jp/)
by [Michael Hartl](http://michaelhartl.com/).


rails generate controller Users new --no-test-framework
rails generate integration_test user_pages
rails generate model User name:string email:string
rails generate migration add_index_to_users_email
rails generate migration add_remember_token_to_users

bundle exec rake db:migrate
bundle exec rake db:test:prepare
bundle exec rake db:reset

bundle exec rspec spec/models/user_spec.rb

シンボル  :exmaple
ハッシュ   exmaple: