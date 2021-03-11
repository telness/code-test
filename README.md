# Number search

Your task is to create a web page to list and search for numbers.

The task should take a few hours to complete and not everything has to be perfect.
Focus on what you think is important and document what you think could have been
improved.

## The task

In the repo there is a file called `numbers.csv`, this is the list of all numbers that should be listed.

Each number has the following fields:

* `msisdn` is the formatted number (see [MSISDN](https://en.wikipedia.org/wiki/MSISDN) for more information about the formatting);
* `grade` is a number that signifies the numbers how valuable the number is (typically the number of
consecutive zeroes), the higher the grade the more expensive it is;
* `type` is what type of number it is (`CELL` for mobile numbers, `FIXED` for landline numbers and `DATA` numbers used only
for data SIM cards);
* `reserved_at` is either empty if the number isn't reserved or a timestamp when the number was reserved;
* `expires_at` is either empty if the number isn't reserved or reserved indefinitely, otherwise it is the
timestamp when the reservation expires.

Your web page should allow filtering by `msisdn` to find numbers by searching for prefixes, suffixes or parts of the number. Additionally it should be possible to filter the numbers by the `grade`, `type` and if the number is reserved.

All information about the number should be visible on the web page.

## Documentation

When sending your code to us include how to install and start the project as well as how to test it.

If you chose to focus less on some parts document what and how they might be improved.

