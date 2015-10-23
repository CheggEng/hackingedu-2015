## Chegg HackingEDU 2015
This repository contains Chegg APIs available for students in [HackingEDU 2015 event](http://hackingedu.co)

### Getting started
* Come to the Chegg booth to register and get your team's API key and secret (and Chegg Swag to boot)!
* Install Google chrome browser `postman` from [https://www.getpostman.com/](https://www.getpostman.com/)
* Import the file `chegg-hackingedu-2015-postman.json` available in this stash repo into POSTMAN
* In POSTMAN configure HTTP Request header as below in every http request call
    * "Authorization: Basic $base64encodedString"
    * Logic to calculate base-64 encoded string is `base64encodedString = encodeBase64(apiKey + ':' + apiSecret)`
* Play around with sample requests in `POSTMAN` to try different Chegg REST services


### Chegg services
Below is the set of Chegg product APIs available for HackingEDU participants
#### Basic Textbook Search
Search for basic information on books by relevant attributes such as title and author, ISBN or EAN.
#### Textbook Catalog (including related items)
Fetch detailed information such as title, author and edition about textbooks or related items. Find related items to a textbook that include recommended books, supplement materials, e-books and textbook solutions.
#### Schools
Search for a school by relevant attributes such as name or state
Fetch school information such as funding type, majors they offer, similar schools, cost statistics 
#### Scholarships
Search for a scholarship by relevant attributes such as name, school type, or state.
Fetch scholarship details such as provider and requirements

### What's the prize?
Along with a chance to win grand prizes given by HackingEDU, special prize will be given for the **Best app using Chegg API**.

**Prize** : Up to $5000 of Chegg Services in total, which include: 1 Year Chegg Textbooks, 1 Year Chegg Study, 4 Hours Chegg Tutoring Sessions for each member of group.


### Got questions/issues?
* **Need API key?** Stop by the Chegg booth, talk to Cheggsters to grab your API key and awesome Chegg Swags!!!!
* **Got Questions?** Chegg volunteers are available at the booth and also online on Gitter Instant messenger at [https://gitter.im/CheggEng/hackingedu-2015](https://gitter.im/CheggEng/hackingedu-2015?utm_source=share-link&utm_medium=link&utm_campaign=share-link)

[![Join the chat at https://gitter.im/CheggEng/hackingedu-2015](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/CheggEng/hackingedu-2015?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
HackingEdu 2015

### Chegg swags
![image](http://s24.postimg.org/uwwj2alat/chegg_swag.jpg)
