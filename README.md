I was looking for a set of files to test a JSON parser and found a
link to [http://www.json.org/JSON_checker/test.zip]. Although not
mentioned on the front page (there are no interior links, not even a contact!),
I used the files anyway. However, some of them have problems.

I also found [https://code.google.com/archive/p/json-test-suite/downloads] but
haven't looked at it yet.

## Issues with the tests

* fail26.json looks like it should have literal tabs (escaped), but the file has spaces.
* fail18.json checks for depth, but there's no requirement that something fail for that. Some parsers do limit that, but it's not a JSON spec

## Some links

* [RFC 7159](https://tools.ietf.org/html/rfc7159) - The JavaScript Object Notation (JSON) Data Interchange Format
* [JSON.org](https://json.org)


## License

You can use my work under the Artistic License 2.0.

These files came to me with no note of a license, but the
[JSON Checker code](http://www.json.org/JSON_checker/). I don't think
this is a valid license since the terms "Good" and "Evil" aren't defined.
Some people already think JavaScript is evil. So how woudl that work?

	/*
	Copyright (c) 2005 JSON.org

	Permission is hereby granted, free of charge, to any person obtaining a copy
	of this software and associated documentation files (the "Software"), to deal
	in the Software without restriction, including without limitation the rights
	to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
	copies of the Software, and to permit persons to whom the Software is
	furnished to do so, subject to the following conditions:

	The above copyright notice and this permission notice shall be included in all
	copies or substantial portions of the Software.

	The Software shall be used for Good, not Evil.

	THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
	IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
	FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
	AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
	LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
	OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
	SOFTWARE.
	*/
