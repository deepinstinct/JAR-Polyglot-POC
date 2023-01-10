# HTML + JAR Polyglot PoC

This repository contain a simple PoC of a polyglot HTML + JAR file.

The purpose of the PoC is to show that JAVA will execute JAR files with any extension and with appended data before the JAR.

To create such file you can simply run in windows command line:
```bash
copy /b dummy.html + suspicious.jar polyglot.html
```

To make the polyglot look better, you need to add a comment in the end of the HTML file so the JAR content won't show when the HTML is rendered in a browser.

This PoC was published as part of the blog about polyglot JAR files:

<add_link_to_blog_here>

## Installation

Make sure you have JAVA runtime installed.

## Usage

```python
java -jar polyglot.html
```


## License

[MIT](https://choosealicense.com/licenses/mit/)