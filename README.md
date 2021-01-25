# Fork of GOV UK's Accessibility Tool Audit

This is a fork of GOV UK's repo, which contains numerous accessibility failures, and can be used to test proposed  <abbr title="W3C Accessibility Guidelines">WCAG</abbr> 3 conformance.

## About the test cases

The test cases are a collection of the wide variety of potential accessibility issues that can exist. This isn't a definitive list of every possible conformance issue, and more will need to be added when WCAG 2.2 becomes a recommendation and WCAG 3 work continues.

## Contributing / updating results

We welcome issues / pull requests for updated or new test cases or tool results. All relevant content can be found in `tests.json`. (All the HTML files are automatically created from that one file.)
Read more on [how to contribute](CONTRIBUTING.md).

## Installing

Make sure you have the gulp command installed beforehand.

```
npm install -g gulp
```

Then run the following commands to install the dependencies and generate the static html files.

```
npm install
gulp

```

Now you can run a local HTTP server to serve the files in this directory. Such as:

```
python -mSimpleHTTPServer
```

and click [http://localhost:8000/](http://localhost:8000/) to see the generated HTML output.

You can also run gulp in dev mode, which would keep watching for files to change until you kill it.

```
gulp dev
```

## Licence

Released under the MIT Licence, a copy of which can be found in the file `LICENCE`.
