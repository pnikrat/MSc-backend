web: bin/rails server -p $PORT -e $RAILS_ENV
worker: bundle exec sidekiq -e staging -q default -q mailers -c 3 -v
