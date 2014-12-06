# A minimum cookbook for Berkshelf

just say "hello world".

## Usage


write Berksfile

```ruby
source "https://supermarket.chef.io"

cookbook 'hello', github: 'DQNEO/cookbook-hello'
```

install cookbook

```
berks vendor cookbooks
```

