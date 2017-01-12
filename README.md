## Bitly API happy and negative paths

# RSpec tests for Bitly URL shortener feature

* Test when URL link is long url
* Test when shorten URL is expanded to full url
* Test when URL returns page title
* Test when URL is already Bitly URL
* Test when URL is an invalid URL

## Gems Used

```ruby
gem 'capybara'
gem 'site_prism'
gem 'selenium-webdriver'
gem 'chromedriver-helper'
gem 'faker'
gem 'bitly'
```

To run all Rspec tests:

```bash
rspec spec
```
