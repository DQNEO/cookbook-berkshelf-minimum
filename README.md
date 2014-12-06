# A minimum cookbook for Berkshelf

All This cookbook does is to say "hello world".

## Usage


write Berksfile

```
source "https://supermarket.chef.io"

cookbook 'hello', github: 'DQNEO/cookbook-hello'
```

install cookbook

```
berks vendor cookbooks
```

