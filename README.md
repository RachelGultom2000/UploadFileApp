## Required Installations:
1. [Ruby](https://www.ruby-lang.org/en/downloads/)
	
2. Ruby on Rails Framwork. From terminal/cmd:
```
gem install rails
```
3. [MYSQL Server](https://dev.mysql.com/downloads/mysql/)



## Project Configurations:
1. Clone 'rails-crud' project to 'your destination'
```
cd 'your destination'
git clone https://github.com/RachelGultom2000/UploadFileApp.git
```

2. Install bundle
```
cd 'uploadfileapp'
bundle install
```
3. Change username/password in 'uploadfileapp/config/database.yml' to match your mysql database username/password:
```ruby
username: 'your username' # your username username
password: 'your password' # your mysql password
localhost: 'your localhost' # localhost default : 127.0.0.1
port: 'your port'# mysql port default : 3306
```

4. Run migrations for the project to build its tables on uploadfileapp_db_dev database:
```
rails db:migrate
```
OR 
```
rake db:migrate  
```

5. Run Server:
```
rails server --port:3000
```
OR
```
rails s
```
OR
```
rails server
```

6. Open your browser, navigate to:
* 'http://127.0.0.1:3000/' for public access


