### How to publish a HTML document with document.do?
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


#### Can I use the stylesheet of document.do?
Yes. See example.


#### Can I use document.do's JS?
Yes. View the source of document.do to find something useful.
