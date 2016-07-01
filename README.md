#This repo is for creating a large scale image data set from World Wide Web.

Will need to install node modules
- async
- bluebird
- cheerio
- EventEmitter
- gm
- iconv
- limiter
- lupus
- nightmare
- request

Generates a hyponym tree using the Natural Language Toolkit and Wordnet based on the keyword entered, then scrapes images from google based on each node in the hyponym tree. The result is a large image data set of related items to the keyword. Images are stored in ./images/


```
python wordnet.py yourkeyword
```
