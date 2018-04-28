# POS using rails [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/neume/posko/tree/develop)
  An open source POS written on rails. Hopefully, it can support real world scenario.


[![Build Status](https://travis-ci.org/neume/posko.svg?branch=develop)](https://travis-ci.org/neume/posko)
[![Maintainability](https://api.codeclimate.com/v1/badges/12cd8cf666a27e7c7b10/maintainability)](https://codeclimate.com/github/neume/posko/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/12cd8cf666a27e7c7b10/test_coverage)](https://codeclimate.com/github/neume/posko/test_coverage)
[![CodeFactor](https://www.codefactor.io/repository/github/neume/posko/badge)](https://www.codefactor.io/repository/github/neume/posko)

# Specs
* Ruby ``` 2.4.2 ```
* Rails ```5.1.6```

# Setting Up
## Database
  This app uses ```postgresql```

  Run ```rake db:create db:migrate db:seed```

### Model Diagram
![Model Diagram][model-diagram]

[model-diagram]: ../develop/doc/models_brief.svg "Model Diagram"

## Running Test
```bundle exec rspec```
# Dashboard Preview

![Preview][preview]

[preview]: ../develop/app/assets/images/sample.png "Preview"

# Mobile App companion
  https://github.com/em4rtinez/posko

# Desktop App
  It will follow after the release of version 1. I plan to utilize the power of ```Electron```

# Contributing
  Contributions/Suggestions are very welcome. https://github.com/neume/posko

# Supported Modules
+ User

# TODOS (Basic Modules)
+ Roles (Ability later)
+ Products
  - composite
+ Variants
+ Collections
+ Orders
+ Payments
+ Customers
+ Cart(ecommerce later)
+ Addresses
+ Contacts
+ Reports(later)
+ Blog(not yet sure)
+ API with Documentation
+ Breadcrumbs
+ Branches
