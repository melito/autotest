Autotest
========

This is based on the wonderful tool "pta" (https://github.com/remogatto/prettytest/tree/master/pta)

I liked this tool and used it a lot while learning Go.

It had two problems I felt.

	* It came packaged with a test formatter / runner suite that I didn't use
	* Everytime I had a project with a directory of assets that didn't include Go code, I'd get a bunch of unneccessary error messages in stdout

This version fixes that and will only watch directories and run `go test` on directories that contain go tests

Getting started
~~~bash
$ go get -v github.com/melito/autotest
~~~

Then launch the <tt>autotest</tt> in your working directory:

~~~bash
$ autotest
~~~

# LICENSE

Copyright (c) 2013 Andrea Fazzi

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