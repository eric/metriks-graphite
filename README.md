# Metriks reporter for Graphite

This is the [metriks](https://github.com/eric/metriks) reporter for graphite.

## How to use it

Sends metrics to Graphite every 60 seconds.

``` ruby
  reporter = Metriks::Reporter::Graphite.new 'localhost', 3004
  reporter.start
```

# License

Copyright (c) 2012 Eric Lindvall

Published under the MIT License, see LICENSE
