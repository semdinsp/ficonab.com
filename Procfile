#web: bundle exec rackup config.ru -p $PORT
#web: bundle exec unicorn config.ru -p $PORT -c ./unicorn.rb
web: bundle exec falcon serve -b http://0.0.0.0:${PORT:-3000} --count 3
#web: bundle exec puma -C puma.rb

