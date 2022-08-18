#web: bundle exec rackup config.ru -p $PORT
#web: bundle exec unicorn config.ru -p $PORT -c ./unicorn.rb
web: bundle exec falcon serve --count 3   -b [::] -p 8080
#web: bundle exec puma -C puma.rb

