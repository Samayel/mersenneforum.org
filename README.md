# mersenneforum.org

## CONTENT

* fundamentals
  * gmp
  * gwnum

* prime factorization
  * gmp-ecm
  * msieve
  * yafu
  * ggnfs
  * cado-nfs
  * ecm.py
  * factmsieve.py

* aliquot sequences
  * aliqueit

* primality tests
  * openpfgw (PrimeForm/GW)

## INSTALL

* run ./build resp. ./build.mingw

## TEST

* prime factorization: ./bin/yafu
  * factor(2056802480868100646375721251575555494408897387375737955882170045672576386016591560879707933101909539325829251496440620798637813)
    * Rho, P-1, ECM and SIQS
  * factor(140870298550359924914704160737419905257747544866892632000062896476968602578482966342704)
    * ECM
  * factor(1522605027922533360535618378132637429718068114961380688657908494580122963258952897654000350692006139)
    * NFS (RSA-100)
  * factor(35794234179725868774991807832568455403003778024228226193532908190484670252364677411513516111204504060317568667)
    * NFS (RSA-110)
* prime factorization: ./bin/cado-nfs.py
  * ./cado-nfs.py 90377629292003121684002147101760858109247336549001090677693
* aliquot sequences: ./aliqueit
  * ecm.py + factmsieve.py via ./aliqueit XXX
  * yafu via ./aliqueit -y XXX
  * XXX = 840
    * height: 49 digits @ 284
    * length: prime 601 @ 746
  * XXX = 3630
    * height: 100 digits @ 1263
    * length: prime 59 @ 2623
  * XXX = 6160
    * height: 96 digits @ 1631
    * length: prime 601 @ 3026
  * XXX = 407856
    * height: 128 digits @ 955
    * length: prime 41 @ 2181

## RECOMMENDED READING

* http://www.mersenneforum.org/showthread.php?t=23078
  * http://www.mersenneforum.org/showpost.php?p=487757&postcount=7
* http://www.starreloaders.com/edhall/AliWin/AliqueitLinstall.html
