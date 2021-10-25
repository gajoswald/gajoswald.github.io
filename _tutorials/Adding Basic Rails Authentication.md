From _Agile Web Development with Rails 6_

Make sure you that you have run `bundle update`

Use the package manager to install bcyrpt

```bash
# assumes the following alias
alias rails="bundle exec bin/rails"
rails generate scaffold User name:string password:digest
```

Update your User model (`app/models/user.rb`) to the following:

```ruby
class User < ApplicationRecord
  validates :name, presence: true, uniqueness: true
  has_secure_password
end
```

changes to views,etc. 

Session and Admin Controllers
```bash
rails generate controller Sessions new create destroy
rails generate controller Admin index
```
