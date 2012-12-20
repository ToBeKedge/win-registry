windows-registry-util
============

100% pure Java, simple Windows registry utility.

[![Build Status](https://secure.travis-ci.org/sarxos/win-registry.png?branch=master)](http://travis-ci.org/sarxos/win-registry)

## Maven Integration

Add dependency to your project:

```xml
<dependency>
	<groupId>com.github.sarxos</groupId>
	<artifactId>windows-registry-util</artifactId>
	<version>0.2</version>
</dependency>
```

## Features

* createKey(HKey, String)
* deleteKey(HKey, String)
* deleteValue(HKey, String, String)
* readString(HKey, String, String)
* readStringSubKeys(HKey, String)
* readStringValues(HKey, String)
* writeStringValue(HKey, String, String, String)

## Limitations

This tool can work with ```HKEY_CURRENT_USER``` and ```HKEY_LOCAL_MACHINE``` only.

## License

Copyright (C) 2011 - 2012 Bartosz Firyn

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
