# Sage X3

Useful Sage X3 ERP code.

## 4GL examples

[Action: SEL_TABLE](4GL_examples/SEL_TABLE.src)

## Functions

### Dates

[Funprog NMONTH(Name of the month, language)](Functions/Dates/YNMONTH.src)

Returns the number of a month, given the name in a language.

[Funprog MIN_DT(Datetime 1, Datetime 2)](Functions/Dates/YMINDT.src)

Returns the number of minutes between two datetimes.

[Funprog GET_EASTER(Year)](Functions/Dates/YGETEASTER.src)

Returns Easter day for the given year.

### Files

[Funprog GET_FILE_IN_DIRECTORY(Path, Files prefix, Files ext, Files only, Subdirectories yes/no, Sort yes/no)](Functions/Files/YGETFILEINDIRECTORY.src)

Returns the SYSTEME2 parameter (i.e. the cmd command) to find all files in a directory.

### Strings

[Subprog CUTSEW(List of strings to modify, list of characters to find)](Functions/Strings/YCUTSEW.src)

Removes all patterns found in the 2nd parameter from the string (or list of strings) in the first parameter.

[Funprog ISITSPECIAL(String to check)](Functions/Strings/YISITSPECIAL.src)

Checks wether a strings contains a special character.

### Generic

[Funprog ANNULLO_MOVCONTABILE(Tipo, Numero movimento)](Functions/Generic/YANULMOVCONT.src)

(ITA) Annulla un movimento contabile, dato il numero ed il tipo.

[Subprog SUPIMPREQ(Print server, job number)](Functions/Generic/YKILLPRINTSERV.src)

Kills a print job.

### Other libraries

[A pure SAGE X3 4GL XML parser.](https://github.com/mc996/mcmaticaX3/blob/main/XMLPARSER/README.md)
