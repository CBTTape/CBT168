# CBT168
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 168 WAS CONTRIBUTED BY BILL GODFREY OF PRC, INC.          *   FILE 168
//*           IN SUITLAND, MD.  THESE ARE UPDATES TO SOME OF        *   FILE 168
//*           IS PROGRAMS IN JIM MARSHALL'S FILES, AND THERE        *   FILE 168
//*           ARE SOME NEW THINGS.  BILL HAS DONE MUCH PIONEERING   *   FILE 168
//*           WORK, AND HIS SOFTWARE DESERVES A GOOD LOOK.          *   FILE 168
//*                                                                 *   FILE 168
//*   email:  Bill.Godfrey@noaa.gov                                 *   FILE 168
//*                                                                 *   FILE 168
//*         MVS SOFTWARE AND MODIFICATIONS                          *   FILE 168
//*         FROM BILL GODFREY, OF PRC INC.                          *   FILE 168
//*         (FORMERLY PLANNING RESEARCH CORPORATION)                *   FILE 168
//*         MCLEAN, VIRGINIA                                        *   FILE 168
//*                                                                 *   FILE 168
//*         MEMBER NAMES ENDING WITH '$' CONTAIN JCL TO             *   FILE 168
//*         ASSEMBLE AND LINK, AND ARE NOT LISTED BELOW.            *   FILE 168
//*                                                                 *   FILE 168
//*         MEMBER NAMES ENDING WITH '#' CONTAIN HELP FOR A         *   FILE 168
//*         TSO COMMAND, AND ARE NOT LISTED BELOW.                  *   FILE 168
//*                                                                 *   FILE 168
//*         $DOC     - THIS FILE YOU ARE READING.                   *   FILE 168
//*         ASMH     - REFRESH OF ASSEMBLER PROMPTER FROM CBT       *   FILE 168
//*                    FILE 300.                                    *   FILE 168
//*         CATPW    - DISPLAY ICF MASTER CATALOG PASSWORDS.        *   FILE 168
//*         COPYPDS  - REFRESH OF COPYPDS TSO COMMAND FROM          *   FILE 168
//*                    CBT FILE 300. ISPF ENQ.                      *   FILE 168
//*         CUTC01   - ISPF/PDF EDIT CLIST 'CUT', PART OF           *   FILE 168
//*                    CUT/PASTE SET.                               *   FILE 168
//*         CUTC02   - ISPF/PDF EDIT CLIST 'PASTE', PART OF         *   FILE 168
//*                    CUT/PASTE SET.                               *   FILE 168
//*         CUTDOC   - DESCRIPTION OF CUT/PASTE.                    *   FILE 168
//*         CUTD01   - INSTALLATION INSTRUCTIONS FOR                *   FILE 168
//*                    CUT/PASTE, SINGLE-USER TEST.                 *   FILE 168
//*         CUTD02   - INSTALLATION INSTRUCTIONS FOR                *   FILE 168
//*                    CUT/PASTE, SYSTEM-WIDE.                      *   FILE 168
//*         CUTH01   - ISPF/PDF PANEL, DISPLAYED WHEN USER          *   FILE 168
//*                    ENTERS "CUT ?"                               *   FILE 168
//*         CUTH02   - ISPF/PDF PANEL, DISPLAYED WHEN USER          *   FILE 168
//*                    ENTERS "PASTE ?"                             *   FILE 168
//*         CUTJ01   - INSTALLATION JCL FOR CUT/PASTE,              *   FILE 168
//*                    SINGLE-USER TEST.                            *   FILE 168
//*         CUTJ02   - INSTALLATION JCL FOR CUT/PASTE,              *   FILE 168
//*                    SYSTEM-WIDE.                                 *   FILE 168
//*         CUTL01   - ISPF/PDF EDIT MACRO 'CUT', PART OF           *   FILE 168
//*                    CUT/PASTE SET.                               *   FILE 168
//*         CUTL02   - ISPF/PDF EDIT MACRO 'PASTE', PART OF         *   FILE 168
//*                    CUT/PASTE SET.                               *   FILE 168
//*         CVD      - TSO COMMAND TO CONVERT A HEX NUMBER TO       *   FILE 168
//*                    DECIMAL.                                     *   FILE 168
//*         CVX      - TSO COMMAND TO CONVERT A DECIMAL             *   FILE 168
//*                    NUMBER TO HEX.                               *   FILE 168
//*         DSPRINT  - TSO COMMAND TO PRINT SYSOUT. SAME            *   FILE 168
//*                    SYNTAX AS IBM'S DSPRINT.                     *   FILE 168
//*                    (fixed for 8-character TSO userids)          *   FILE 168
//*         FINDAZAP - UTILITY TO FIND A STRING IN A LOAD           *   FILE 168
//*                    MODULE, GENERATE A ZAP.                      *   FILE 168
//*         MEMBER   - REFRESH OF MEMBER TSO COMMAND FROM           *   FILE 168
//*                    CBT FILE 300. XA FIX.                        *   FILE 168
//*         SHOWDS   - REFRESH OF SHOWDS TSO COMMAND  FROM          *   FILE 168
//*                    CBT FILE 300. XA FIX.                        *   FILE 168
//*         ULXDOC   - INFORMATION ABOUT THE ULX... MEMBERS.        *   FILE 168
//*         ULX...   - ISPF PROGRAM FOR DISPLAYING FREE SPACE       *   FILE 168
//*                    ON A DISK VOLUME.                            *   FILE 168
//*         XBE      - EXECUTE ISPF BROWSE OR EDIT VIA              *   FILE 168
//*                    SHORTCUT.                                    *   FILE 168
//*         XBEDOC   - INSTRUCTIONS FOR USING XBE.                  *   FILE 168
//*                                                                 *   FILE 168
//*         THE FOLLOWING NAMING CONVENTION HAS BEEN USED FOR       *   FILE 168
//*         MEMBERS THAT ARE PARTS OF AN ISPF APPLICATION:          *   FILE 168
//*                                                                 *   FILE 168
//*            THE FIRST 3 CHARACTERS IDENTIFY THE APPLICATION.     *   FILE 168
//*            THE 4TH CHARACTER IS                                 *   FILE 168
//*                  'L' FOR SOURCE CODE OF LOAD MODULES            *   FILE 168
//*                  'D' FOR DOCUMENTATION                          *   FILE 168
//*                  'P' FOR PANEL        'H' FOR TUTORIAL PANEL    *   FILE 168
//*                  'M' FOR MESSAGE SET  'C' FOR CLIST             *   FILE 168
//*                  'S' FOR SKELETON     'J' FOR JCL               *   FILE 168
//*            THE 5TH AND 6TH CHARACTERS ARE NUMBERS THAT          *   FILE 168
//*            UNIQUELY IDENTIFY EACH MODULE WITHIN THE GROUP.      *   FILE 168
//*                                                                 *   FILE 168
//*            THE NAMING CONVENTION FITS WITHIN THE NAMING         *   FILE 168
//*            REQUIREMENTS FOR MEMBERS OF THE ISPF MESSAGE         *   FILE 168
//*            LIBRARIES.                                           *   FILE 168
//*                                                                 *   FILE 168
```
