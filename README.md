# Diary
A script for writing a diary.

## Configuration
By default the entries are stored in `$HOME/.diary/`. Export `$DIARY` to
change that directory.

## Writing a diary
To create or edit an entry for the current day:

    diary

To create or edit an entry for a specific day:

    diary write 2016 09 30

## Reading a diary
To read all entries:

    diary read

To read all entries from a specific year:

    diary read 2016

To read all entries from a specific month:

    diary read 2016 09

To read an entry from a specific day:

    diary read 2016 09 30
