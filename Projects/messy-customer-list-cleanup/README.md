# Messy Customer List Cleanup

A messy made-up customer list cleaned in Excel, with the raw data and each cleaning step side by side.

## Problem it solves
Raw customer data often has duplicates, extra spaces and inconsistent capitalisation. This project cleans it into a usable list.

## How to use it:
1. Open [messy-customer-cleanup.xlsx](messy-customer-cleanup.xlsx)

## What I used
* `TRIM` to remove extra leading and trailing spaces
* `PROPER` to fix inconsistent capital letters in customer names and cities
* `LOWER` to standardise email addresses
* Remove Duplicates (Data tab) to remove repeated customer records

## How to use it
1. Open -> (messy-customer-list-cleanup/messy-customer-cleanup.xlsx)
2. Read the sheet left to right. It starts with the raw data, moves through the formula columns (`TRIM`, then `PROPER` and `LOWER`), and ends with the final clean table on the right.

## What I learned
* Putting each cleaning step in its own column, side by side, makes it easy to spot mistakes before building the final clean table.

## What I'd improve
* Put the raw data and the final cleaned output on two separate sheets (`raw-data` and `clean-data`).

All data in this project is made up.