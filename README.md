# README

This is example for "NameError: uninitialized constant ActiveSupport::ParameterFilter" in RSpec with Rails7.
Follow the steps below to reproduce.

1. Run Docker

```
$ make build
$ make up
```

2. Run RSpec in Docker container

```
$ make bash
# rails db:migrate
# rspec
```
