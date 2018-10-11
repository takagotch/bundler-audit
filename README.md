### bundler-audit
---

https://github.com/rubysec/bundler-audit

```ruby
require 'bundler/audit/task'
Bundler::Audit::Task.new
task default: 'bundle:audit'

```

```
# Gemfile.lock
bundle audit
bundle audit update
bundle audit check --update
bundle audit check --ignore OSVDB-108664
gem install bundler-audit


```

