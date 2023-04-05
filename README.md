### How to publish a HTML document on Polygon with document.do?
Start your document with:
```
<!DOCTYPE html>
```

### How is the document parsed?
The document will replace the entire document.do interface with:
```
document.write($content_of_document);
```

### FAQ

#### Can I load/call external sources?
For safety reasons you can't.

#### Can I add multiple pages?
Yes, with a [router](https://github.com/document-do/router).

#### Can I use the stylesheet of document.do?
Yes. See [example](https://github.com/document-do/html-document/blob/main/examples/document.do.css.html).


#### Can I use document.do's JS?
Yes. See [example](https://github.com/document-do/html-document/blob/main/examples/document.do.js.html). View [min.js](https://github.com/document-do/web/blob/main/min.js) to find something useful. Don't be evil.
