myrecipes app

Testing Framework

Minitest(Default)

RSpec

Layout of the application 

Integration Testing(entire feature)

Model Tests -unit testing(small piece)

rails g integration_test pages

for running test

simply run

rails test


TDD - design the app functionality based on a test first approach
write the test for the functionality
build minimum code necessary to make each test 

Re-factor the code - "code doesnt smell" -clean code, confidence

----Important Gems--
https://github.com/twbs/bootstrap-sass
-gem 'bootstrap-sass', '~> 3.3.6';
----- ----- -----
Database and 1:m association
-Relational Database
-SQL -Structured Query Language
-ActiveRecord - abstraction
-Ruby -translated to SQL
---- ----- ---- ----- 
Database layer, Associations
1:m, m:m
ORM: Object Relational Mapper
has_many
belongs_to
virtual attributes are
ORM
