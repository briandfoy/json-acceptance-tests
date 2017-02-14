I was looking for a set of files to test a JSON parser and found a
link to [http://www.json.org/JSON_checker/test.zip]. Although not
mentioned on the front page (there are no interior links, not even a contact!),
I used the files anyway. However, some of them have problems.

I also found [https://code.google.com/archive/p/json-test-suite/downloads] but
haven't looked at it yet.

## Issues with the tests

* fail26.json looks like it should have literal tabs (escaped), but the file has spaces.
* fail18.json checks for depth, but there's no requirement that something fail for that. Some parsers do limit that, but it's not a JSON spec

