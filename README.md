PIRSdocs
========

PIRS documentation in html generated with Sphinx-doc. This repository contains only auto-generated files; the source for documentation is located at another place. Documentation itself can be viewed at http://travleev.github.io/PIRSdocs/ 

To update files here: 

```
$> mkdir pirsdocs
$> cd pirsdocs
$> git clone https://github.com/travleev/PIRSdocs.git
$> cd PIRSdocs
$> cp -r path/to/html/files/generated/with/sphinx/* .
$> git add *
$> git commit -m "Log message"
$> git push
```

A change.
