# Popular And Useful Rails Gems
  *Here I'm listing some popular and useful 
  gems which I have used in my projects. later I will add implementation and demo of these 
gems.*



### [Dry Validation](https://github.com/dry-rb/dry-validation)
```ruby
gem 'dry-validation'
```
> dry-validation is a data validation library that provides a powerful DSL for defining schemas and validation rules.

> Validations are expressed through contract objects. A contract specifies a schema with basic type checks and any additional rules that should be applied. Contract rules are applied only once the values they rely on have been succesfully verified by the schema.



### [Validates timeliness](https://github.com/adzap/validates_timeliness)
```ruby
gem "validates_timeliness"
```
> Date and time validation plugin for ActiveModel and Rails.Adds validation for dates, times and datetimes to ActiveModel.Handles timezones and type casting of values for you



### [Phonelib](https://github.com/daddyz/phonelib)
```ruby
gem  'phonelib'
```
  > Phonelib is a 
gem allowing you to validate phone number. All validations are based on Google libphonenumber. Currently it can make basic validations and formatting to e164 international number format and national number format with prefix. But it still doesn't include all Google's library functionality.



### [Timeliness](https://github.com/adzap/timeliness) 
```ruby
gem "timeliness"
```
> Date/time parser for Ruby. It's pretty fast. Up to 60% faster than Time/Date parse method.



### [TimeCop](https://github.com/travisjeffery/timecop)
```ruby
gem 'timecop'
```
> A gem providing "time travel" and "time freezing" capabilities, making it dead simple to test time-dependent code. It provides a unified method to mock Time.now, Date.today, and DateTime.now in a single call.



### [SimpleCov](https://github.com/colszowka/simplecov)
```ruby
gem 'simplecov'
```
> SimpleCov is a code coverage analysis tool for Ruby. It uses Ruby's built-in Coverage library to gather code coverage data, but makes processing its results much easier by providing a clean API to filter, group, merge, format, and display those results, giving you a complete code coverage suite that can be set up with just a couple lines of code.

>In most cases, you'll want overall coverage results for your projects, including all types of tests, Cucumber features, etc. SimpleCov automatically takes care of this by caching and merging results when generating reports, so your report actually includes coverage across your test suites and thereby gives you a better picture of blank spots.



### [Capybara](https://github.com/teamcapybara/capybara)
```ruby
gem 'capybara'
```
> Capybara helps you test web applications by simulating how a real user would interact with your app. It is agnostic about the driver running your tests and comes with Rack::Test and   ```rubySelenium support built in. WebKit is supported through an external 
gem.



### [Factory Bot](https://github.com/thoughtbot/factory_bot)
```ruby
gem 'factory_bot'
```
> factory_bot is a fixtures replacement with a straightforward definition syntax, support for multiple build strategies (saved instances, unsaved instances, attribute hashes, and stubbed objects), and support for multiple factories for the same class (user, admin_user, and so on), including factory inheritance.



### [Faker](https://github.com/faker-ruby/faker)
```ruby
gem 'faker'
```
> Faker, a port of Data::Faker from Perl, is used to easily generate fake data: names, addresses, phone numbers, etc.



### [Rollbar-gem](https://github.com/rollbar/rollbar-gem)
```ruby
gem "rollbar"
```
> Rollbar is a real-time exception reporting service for Ruby and other languages. The Rollbar service will alert you of problems with your code and help you understand them in a ways never possible before. We love it and we hope you will too.



### [Better Errors](https://github.com/BetterErrors/better_errors)
```ruby
gem 'better_errors'
```
> Better Errors replaces the standard Rails error page with a much better and more useful error page. It is also usable outside of Rails in any Rack app as Rack middleware.



### [RuboCop](https://github.com/rubocop-hq/rubocop/)
```ruby
gem 'rubocop'
```
> RuboCop is a Ruby static code analyzer (a.k.a. linter) and code formatter. Out of the box it will enforce many of the guidelines outlined in the community Ruby Style Guide.




### [Mongo Driver For Ruby](https://github.com/mongodb/mongo-ruby-driver)
```ruby
gem 'mongo'
```
> A Ruby driver for MongoDB



### [Active Model Serializers](http://github.com/rails-api/active_model_serializers)
```ruby
gem 'active_model_serializers'
```
> ActiveModel::Serializers allows you to generate your JSON in an object-oriented and convention-driven manner.



### [Draper](https://github.com/drapergem/draper)
  ```ruby
gem 'draper' 
```
> Decorators/View-Models for Rails Applications




## [Elasticsearch](https://github.com/elastic/elasticsearch-ruby)
```ruby
gem 'elasticsearch'
```
> Ruby integrations for Elasticsearch (client, API, etc.)



### [Ransack](https://github.com/activerecord-hackery/ransack)
```ruby
gem 'ransack'
```
> Ransack is a rewrite of MetaSearch created by Ernie Miller and developed/maintained for years by Jon Atack and Ryan Bigg with the help of a great group of contributors. Ransack's logo is designed by Anıl Kılıç. While it supports many of the same features as MetaSearch, its underlying implementation differs greatly from MetaSearch, and backwards compatibility is not a design goal.



### [MailForm](https://github.com/plataformatec/mail_form)
```ruby
gem 'mail_form'
```
> MailForm allows you to send an e-mail straight from a form. For instance, if you want to make a contact form just the following lines are needed (including the e-mail)



### [Letter Opener](https://github.com/ryanb/letter_opener)
```ruby
gem 'letter_opener'
```
> Preview email in the default browser instead of sending it. This means you do not need to set up email delivery in your development environment, and you no longer need to worry about accidentally sending a test email to someone else's address.



### [Comfy Blog](https://github.com/comfy/comfy-blog)
  ```ruby
gem "comfy_blog", 
```
> CMS in Rails. Blog Engine for ComfortableMexicanSofa



### [Ckeditor](https://github.com/galetahub/ckeditor)
  ```ruby
gem "ckeditor"
```
> CKEditor is a WYSIWYG text editor designed to simplify web content creation. It brings common word processing features directly to your web pages. Enhance your website experience with our community maintained editor  



### [Remotipart](https://github.com/JangoSteve/remotipart)
  ```ruby
gem 'remotipart' 
```
> Rails jQuery file uploads via standard Rails "remote: true" forms.



### [Lobibox In Rails](https://github.com/thecodeholic/lobibox)
```ruby
gem "rails-assets-arboshiki--lobibox"
```
### [Demo](https://gem-demo.herokuapp.com/gem_demos/lobibox)

> Responsive jQuery notification plugin written from scratch.






### [Datatables In Rails](https://github.com/DataTables/DataTables)
```ruby
gem "rails-assets-datatables.net-bs"
```
>DataTables is a table enhancing plug-in for the jQuery Javascript library, adding sorting, paging and filtering abilities to plain HTML tables with minimal effort. The stated goal of DataTables is:



### [Fusioncharts In Rails](https://www.fusioncharts.com/)
```ruby
gem "rails-assets-fusioncharts"
```
> The most comprehensive JavaScript charting library, with over 100+ charts and 2000+ maps. Integrated with all popular JavaScript frameworks and server-side programming languages



### [Malihu Custom Scrollbar Plugin In Rails](https://github.com/malihu/)
  ```ruby
gem "rails-assets-malihu-custom-scrollbar-plugin"
```
> Highly customizable custom scrollbar jQuery plugin, featuring vertical/horizontal scrollbars, scrolling momentum, mouse-wheel, keyboard and touch support etc.



### [Select2-rails](https://github.com/argerim/select2-rails)
  ```ruby
gem "select2-rails"
```
> Integrate Select2 javascript library with Rails asset pipeline.



### [Pdfkit](https://github.com/pdfkit/pdfkit)
  ```ruby
gem 'pdfkit'
```
> A Ruby gem to transform HTML + CSS into PDFs using the command-line utility wkhtmltopdf.



### [Spreadsheet](https://github.com/zdavatz/spreadsheet)
  ```ruby
gem "spreadsheet"
```
> The Spreadsheet Library is designed to read and write Spreadsheet Documents. As of version 0.6.0, only Microsoft Excel compatible spreadsheets are supported. Spreadsheet is a combination/complete rewrite of the Spreadsheet::Excel Library by Daniel J. Berger and the ParseExcel Library by Hannes Wyss. Spreadsheet can read, write and modify Spreadsheet Documents.



### [Roo](https://github.com/roo-rb/roo)
  ```ruby
gem "roo"
```
> Roo implements read access for all common spreadsheet types.



### [Rails ERD](https://github.com/voormedia/rails-erd)
  ```ruby
gem "rails-erd"
```
> Generate Entity-Relationship Diagrams for Rails applications



### [Guard Live Reload](https://github.com/guard/guard-livereload)
  ```ruby
gem guard-livereload""
```
> LiveReload guard allows to automatically reload your browser when 'view' files are modified.



### [Site Prism](https://github.com/site-prism/site_prism)
  ```ruby
gem "site_prism"
```
> SitePrism gives you a simple, clean and semantic DSL for describing your site using the Page Object Model pattern, for use with Capybara in automated acceptance testing



### [Database Cleaner](https://github.com/DatabaseCleaner/database_cleaner)
  ```ruby
gem "database_cleaner"
```
> Database Cleaner is a set of strategies for cleaning your database in Ruby.


### [Social Share Button](https://github.com/huacnlee/social-share-button)
  ```ruby
gem 'social-share-button'
```
> Helper for add social share feature in your Rails app. Facebook, Twitter, Douban, Google+, Weibo, QZone, Google Bookmark, Delicious, Tumblr, Pinterest, Email, LinkedIn, WeChat (Weixin), Vkontakte, Odnoklassniki, Xing, Reddit, Hacker News, Telegram, WhatsApp.



### [Rack Cors](https://github.com/cyu/rack-cors)
  ```ruby
gem 'rack-cors' 
```
> Rack Middleware for handling Cross-Origin Resource Sharing (CORS), which makes cross-origin AJAX possible.



### [Any Login](https://github.com/igorkasyanchuk/any_login)
  ```ruby
gem 'any_login'
```
> Easy way to login as any user in system.



### [Wicked](https://github.com/schneems/wicked)
```ruby
gem 'wicked'
```
> Use wicked to make your Rails controllers into step-by-step wizards



### [Rack Attack](https://github.com/kickstarter/rack-attack)
```ruby
gem 'rack-attack' 
```
> Protect your Rails and Rack apps from bad clients. Rack::Attack lets you easily decide when to allow, block and throttle based on properties of the request



### [Friendly Id](https://github.com/norman/friendly_id)
```ruby
gem 'friendly_id' 
```
> FriendlyId is the “Swiss Army bulldozer” of slugging and permalink plugins for ActiveRecord. It allows you to create pretty URL’s and work with human-friendly strings as if they were numeric ids for ActiveRecord models.



###  [Public Activity](https://github.com/chaps-io/public_activity)
  ```ruby
gem 'public_activity'
```
> public_activity provides easy activity tracking for your ActiveRecord, Mongoid 3 and MongoMapper models in Rails 3.0 - 5.0. Simply put: it records what has been changed or created and gives you the ability to present those recorded activities to users - in a similar way to how GitHub does it.



### [Amoeba](https://github.com/amoeba-rb/amoeba)
```ruby
gem amoeba""
```
> A ruby 
gem to allow the copying of ActiveRecord objects and their associated children, configurable with a DSL on the model



### [Paranoia](https://github.com/rubysherpas/paranoia)
```ruby
gem 'paranoia' 
```
> ActiveRecord plugin allowing you to hide and restore records without actually deleting them. 



### [JWT Token](https://github.com/jwt/ruby-jwt)
  ```ruby
gem 'jwt' 
```
> A ruby implementation of the RFC 7519 OAuth JSON Web Token (JWT) standard.



### [Paper Trail](https://github.com/paper-trail-gem/paper_trail)
  ```ruby
gem "paper_trail"
```
> Track changes to your models, for auditing or versioning. See how a model looked at any stage in its lifecycle, revert it to any version, or restore it after it has been destroyed



### [AASM](https://github.com/aasm/aasm)
  ```ruby
gem "aasm"
```
> Adding a state machine is as simple as including the AASM module and start defining states and events together with their transitions:



### [AWS SDK S3](https://github.com/aws/aws-sdk-ruby)
  ```ruby
gem "aws-sdk-s3"
  ```
> aws-sdk gem contains every available AWS service 
gem support. Please use a major version when expressing a dependency on aws-sdk



### [To Words](https://github.com/taimur-akhtar/to_words)
  ```ruby
gem "to_words"
```
> converts numbers into words
