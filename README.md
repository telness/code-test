## Phone number search

Your task is to create a web page, similar to one that already exists on Telness, where users can list and search for phone numbers.

## Description

Your web page should:
* allow filtering by `msisdn` to find phone numbers by searching for
    * a specific prefix,
    * a specific suffix,
    * or a substring of the number;
* as well as support writing the number both as `msisdn` (+46712) or as a mobile number (0712);
* filter the phone numbers by `grade`, `type` or if it is reserved or not;
* show all information about each field in the table.

### Data

In the repo there is a file called `numbers.csv`, that contains a list of the numbes to show on the web page.

Each number has the following fields:

* `msisdn` is the formatted number (see [MSISDN](https://en.wikipedia.org/wiki/MSISDN) for more information about the formatting);
* `grade` is a number signifying the how valuable the number is (the higher the number, the more costly it is);
* `type` is either `CELL` for mobile numbers or `FIXED` for landline numbers;
* `reserved_at` is either empty if the number isn't reserved or a timestamp when the number was reserved;
* `expires_at` is either empty if the number isn't reserved or reserved indefinitely, otherwise it is the timestamp when the reservation expires.

## Submission

You should submit your code by using [`git bundle`](https://git-scm.com/docs/git-bundle.html) and sending the bundled file via mail.

_* Your work will not be used in the Telness product or in any part of such product, the only purpose is to test your technical skills._

## Requirements

* Your submission should include a `README.md` file documenting how to install and start the project;
* You won't have the time to make everything perfect, just document what is lacking and how you would improve it;
* Do not make the task harder than it is, it should take a couple of hours but absolutely not more than 8 hours;
* You are free to use any technology and framework of your choice;
