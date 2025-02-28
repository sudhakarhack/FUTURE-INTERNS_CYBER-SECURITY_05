Email Meta Analysis
=====
Ever wonder what was in your email?

I did, so I wrote some python scripts to analyze it! 

You can check out the analysis of my own email [on my website](http://austingwalters.com/analyzing-email-data/)

## Usage

* Must place python scripts in the same folder as mbox
* Rename .mbox as 'mail.mbox'
* Need folder wordFrequency (should be present)
* Add name or any other words to skip to stdWords.csv
* Run <filename>.py as desired
* Wait ~2 minutes per Gb
* Load .csv into excel or sheets

## Required Tuning

* Everyone has different *spam*, either edit scripts or remove on .csv
* Edit stdWords.csv to skip words when analyzing frequency
* To make graphs I used Google Sheets, I removed common words
* I recommend adding companies to stdWords.csv, especially if you receive updates

## Minor Disclaimer

I wrote this *extremely* rough collection of scripts which work well for me with minor editing.

I make no claims they will work for you, and if you make any upgrades please merge them in! :)
