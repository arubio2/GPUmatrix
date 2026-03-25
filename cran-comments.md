## Maintainer change
The previous maintainer, César Lobato, was a PhD student who has now finished his thesis and left the lab. 
I (Angel Rubio), as the principal investigator / co-author, am taking over the maintenance of the package.

## Resubmission
This is a resubmission to restore the package to CRAN after it was archived due to check failures with recent R updates. 

In this version (1.0.3), we have fixed all the issues that caused the archival:
* Fixed the `fft(x)` non-numeric argument error in examples by specifying the argument explicitly.
* Fixed the missing package anchors in Rd \link{} targets (e.g., Matrix-class, %&%).
* Added the missing documentation and @aliases for S4 methods (`dimnames<-` for vector and ANY).

## R CMD check results
0 errors | 0 warnings | 0 notes

Tested on R 4.5.3 (Windows) using devtools::check().
