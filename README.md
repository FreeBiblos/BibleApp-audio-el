# BibleApp-audio-el

Recorded audio for the Greek texts in the [KJV Bible app](https://bluesboy13.github.io/BibleApp/):
the Septuagint (Brenton's Greek, with the extra books) and the Greek New Testament (Scrivener's 1894
Textus Receptus), read in modern Greek pronunciation by the built-in Greek voice of
[Chatterbox Multilingual](https://github.com/resemble-ai/chatterbox) (MIT).

Layout: `<book 01-80>/<chapter 001>.m4a` plus `.json` verse timings. Books 1-66 follow the KJV order;
67-80 are the extra Septuagint books. Served by GitHub Pages; recorded by `.github/workflows/record.yml`.
