# NexmoCli

===

Simple Bash Script to send SMS using the Nexmo Gateway.
Copy *.nexmo* into your *$HOME* Folder and the *nexmo* script into */usr/local/bin*

```
cp .nexmo ~/ && cp nexmo /usr/local/bin
```

then customize *.nexmo* and enter your API_KEY and API_SECRET like so:

```
vim ~/.nexmo
```

after entering your credentials, send SMS using your commandline, the format is as follows:

**nexmo** *SENDER* *RECIPIENT* *TEXT*

e.g.

```
nexmo 0012025550168 0016135550102 "Hey mate!"
```


**The MIT License (MIT)**

Copyright (c) 2014 Marcus Kida

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.