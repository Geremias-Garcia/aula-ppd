FROM ruby:3.2

WORKDIR /app

COPY . /app

RUN gem install bundler && bundle install

EXPOSE 4567

CMD ["ruby", "app.rb", "-o", "0.0.0.0"]
