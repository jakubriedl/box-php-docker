#box-php-docker

Wercker box for php docker applications with preinstalled composer

See the boxes section on [dev center](http://devcenter.wercker.com/articles/boxes)

Source:
https://github.com/jakubriedl/box-php-docker

use this with wercker; in your wercker.yml file:

``` yaml
box: jakubriedl/php-docker
```

Status on wercker:

[![wercker status](https://app.wercker.com/status/340fba21eb03dfa34c5d3ebcf9a2ae0c/m/master "wercker status")](https://app.wercker.com/project/bykey/340fba21eb03dfa34c5d3ebcf9a2ae0c)

## License

The MIT License (MIT)

Copyright (c) 2013 wercker

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Changelog

### 0.0.4

- revert to wercker-labs/docker parent because its required by wercker

### 0.0.3

- fix docker installation

### 0.0.2

- Inherits from Ubuntu 14.04
- Docker 1.5
- PHP bundled with ubuntu 

### 0.0.1

- Initial version