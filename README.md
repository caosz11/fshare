# DUE TO NEW SESSION MECHANISM OF FSHARE, THE CODE IS NOT WORKING ANYMORE.

# Fshare Link Generator

A premium link generator for Fshare.

## Installation

Check out this repository and deploy to OpenShift. [Demo](https://tvhung83.github.io/fshare).

## Usage

To use FshareClient:

```python
from fshare_client import FshareClient

client = FshareClient()
if client.login('YOUR_FSHARE_EMAIL', 'YOUR_FSHARE_PASSWORD'):
	print client.process('https://www.fshare.vn/file/XXXXXXXXXXXX')
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

### v0.5.0:
* Extract main logic to new class.
* Validate login result.
* Stay away from 3<sup>rd</sup> party library, in order to integrate into XBMC later.

## Credits

## The MIT License (MIT)

Copyright (c) 2015 tvhung83

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
