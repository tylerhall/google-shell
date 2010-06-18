Google Search Shell
=========

A programatic interface to Google's search results.

COMMAND LINE USAGE
-------

Place `gshell` somewhere in your path and make it executable.

    Usage: gshell [OPTION]... QUERY
    Programatic interface to Google's search resutls.
    
    -c, --count      number of results to return
    -n, --number     returns only the nth result
    -u, --url        returns only the results' urls
    -t, --title      returns only the results' title
    -a, --abstract   returns only the results' abstract
    -j, --json       format results in json
    -f, --no-format  returns results without any additional formatting
        --help      display this message and exit

    Examples:
        gshell "American Beauty" // Returns full list of results
        gshell -c3 "American Beauty" // Returns the top three results
		URL=`gshell -fun1 "American Beauty"`; curl $URL // Does an "I'm Feeling Lucky" search and downloads the page

UPDATES
-------

Code is hosted at GitHub: [http://github.com/tylerhall/google-shell](http://github.com/tylerhall/google-shell)

LICENSE
-------

The MIT License

Copyright (c) 2010 Tyler Hall &lt;tylerhall AT gmail DOT com&gt;

[http://clickontyler.com](http://clickontyler.com)

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