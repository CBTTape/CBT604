# CBT604
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 604 is the SIT SNOBOL4 Ý*¨ load module version3.5 .       *   FILE 604
//*                                                                 *   FILE 604
//*           It has been updated since the former version was      *   FILE 604
//*           broken.                                               *   FILE 604
//*                                                                 *   FILE 604
//*           I used the IEHMOVE version of the library provided    *   FILE 604
//*           by Jay as a het tape (tar.gz). Reading Jan's DOC is   *   FILE 604
//*           fun.                                                  *   FILE 604
//*                                                                 *   FILE 604
//*           Although it was possible to fix or reconstruct source *   FILE 604
//*           from comments of the disassembly, the result was not  *   FILE 604
//*           nice.                                                 *   FILE 604
//*           Since the whole thing has mainly a historical goal    *   FILE 604
//*           I invested some time to create a understanadable      *   FILE 604
//*           source.                                               *   FILE 604
//*                                                                 *   FILE 604
//*           This new version has been created mostly using the    *   FILE 604
//*           disassembler DISASM from Gerhard Postpischil.         *   FILE 604
//*                                                                 *   FILE 604
//*           The main module S4 is a mix of disassmbled code       *   FILE 604
//*           and comments from the SIL implementation available    *   FILE 604
//*           originally from the University of Arizona and others  *   FILE 604
//*           such as the Michigan Terminal System.                 *   FILE 604
//*                                                                 *   FILE 604
//*           The comments have been added by 'running mate' tp     *   FILE 604
//*           DISASM (about 300 lines of SPITBOL Ý**¨               *   FILE 604
//*                                                                 *   FILE 604
//*           The disassembled source can also be generated on TK5. *   FILE 604
//*                                                                 *   FILE 604
//*           The SUBR section is original source code slightly     *   FILE 604
//*           patched in order to create modules identical to       *   FILE 604
//*           the original one (without garbage from DS holes).     *   FILE 604
//*           The Fortran I/O routines are just the disassembled    *   FILE 604
//*           versions. There is a problem with DD concatenation.   *   FILE 604
//*                                                                 *   FILE 604
//*           The provided load module in this package has the same *   FILE 604
//*           TXT part as the original one, only the CESD and RLD   *   FILE 604
//*           parts are different but equivalent. I haven't tried   *   FILE 604
//*           IEWL from OS360.                                      *   FILE 604
//*                                                                 *   FILE 604
//*           Documentation for SNOBOL is huge. www.snobol.org .com *   FILE 604
//*           archive.org has a good collection of important books, *   FILE 604
//*           Some are recent scans from 2024.                      *   FILE 604
//*                                                                 *   FILE 604
//*           The Michigan Terminal system has a good chapter about *   FILE 604
//*           SNOBOL4 and SPITBOL including information not found   *   FILE 604
//*           elsewhere.                                            *   FILE 604
//*           There are many other SNOBOL4 implementations.         *   FILE 604
//*           Robert Gaskin's book/tutorial uses a Berkeley system. *   FILE 604
//*                                                                 *   FILE 604
//*           SNOBOL is a languguage for humanities.                *   FILE 604
//*                                                                 *   FILE 604
//*           SPITBOL 370 Ý***¨ on SYSCPK is at least a magnitude   *   FILE 604
//*           faster. For any practical purpose, use SPITBOL 370.   *   FILE 604
//*                                                                 *   FILE 604
//*           email:  peter.sylvester@gmail.com peter@edelweb.eu    *   FILE 604
//*                                                                 *   FILE 604
//*      Ý*¨ The original SNOBOL4 implementation from Bell          *   FILE 604
//*      Telephone Laboratories was developed by R. E. Griswold     *   FILE 604
//*      and I. Polonsky, the designers of the SNOBOL4              *   FILE 604
//*      programming language. Thus, this reference                 *   FILE 604
//*      implementation is often referred to as BTL SNOBOL4. In     *   FILE 604
//*      the early 1970s, after Griswold left BTL for The           *   FILE 604
//*      University of Arizona and continued SNOBOL4 distribution   *   FILE 604
//*      from there, this implementation gained another name: SIL   *   FILE 604
//*      SNOBOL4. (SIL = SNOBOL4 Implementation Language)           *   FILE 604
//*                                                                 *   FILE 604
//*      Ý**¨ SPITBOL = SPeedy ImplemenTation of SNOBOL4            *   FILE 604
//*                     --     -       -            ---             *   FILE 604
//*                                                                 *   FILE 604
//*      Ý***¨ SPITBOL 370 superceded SPITBOL 360 which was         *   FILE 604
//*      distributed from 1971 until 1984.                          *   FILE 604
//*                                                                 *   FILE 604
```
