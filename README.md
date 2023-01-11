

# HTML + JAR Polyglot PoC

This repository contain a simple PoC of a polyglot HTML + JAR file.

The purpose of the PoC is to show that JAVA will execute JAR files with any extension and with appended data before the JAR.

To create such file you can simply run in windows command line:
```bash
copy /b dummy.html + suspicious.jar polyglot.html
```

To make the polyglot look better, you will need to add a comment in the end of the HTML file so the JAR content won't be shown when the HTML is rendered in a browser.

This PoC was published as part of the blog about polyglot JAR files:

https://www.deepinstinct.com/blog/malicious-jars-and-polyglot-files-who-do-you-think-you-jar

## Installation

Make sure you have JAVA runtime installed.

## Usage

```python
java -jar polyglot.html
```


## Disclaimer
The code provided is offered as-is and is intended for educational or informational purposes only. The user assumes all responsibility for the use of this code and any consequences that may arise from its use. The creator of this code and its affiliates cannot be held liable for any damages or losses resulting from the use of this code
