# texlog_extract
|     key | description
|     ---:|:---
|  script | texlog_extract - extract errors and warnings from TeX logs
|    type | ruby
|  author | Wybo Dekker
|   email | wybo@dekkerdocumenten.nl
| version | 3.04
| license | GNU General Public License

texlog_extract is a Ruby script that extracts a TeX log file, keeping
track of the files in which errors and warnings occur and, for each
file, reports warnings, the first error (if any), and the error‘s line
number. The output comes on standard output in ASCII, ANSI-colored
ASCII or HTML.
