---
title: Store Locator API Reference

language_tabs:
  - shell
  - ruby

toc_footers:
  - <a href='#'>Sign Up for a Developer Key</a>

includes:
  - errors

search: true
---

# Introduction

Next Generation Bridge API.

# Authentication

> Replace `SECRET_KEY` with your API key.

```ruby
require 'slapi'

Slapi::Client.authorize!('SECRET_KEY')
```

```shell
curl "/" -H "Authorization: SECRET_KEY"
```

The API key needs to be included in all API requests to the server in a header that looks like the following:

`Authorization: SECRET_KEY`

<aside class="notice">
You must replace `SECRET_KEY` with your personal API key.
</aside>