# bmtl course

## Text

For the course, use Bill Quall's "Mainframe Assembler Programming" available from http://billqualls.com/assembler/ for the instruction.

## Changes
Bill uses pc370 which was shareware.  It has beeb replaced by z390 project on SourceForge that can be used for both Windows and Linux.  There is also a project on github (z390-org/z390) that has made changes to the SourceForge content but those changes are not compatible with Linux.  The z390 project was created by the same persons that created the pc379 shareware. 

### Changes needed to update z390 java version.

In tz390, Find the list of java jdks and ensure that the following lines are added:
(Ubuntu)
(Private Build)

This ensures that new versions of openjdk can be used.

### Changes needed to Bill Quall's programs.

#### WTO
 WTO with a string message as part of the instruction have no changes.
 
 WTO references a data area need to change as follows:
 
 #### DCB
 
 DCB changes for RECFMT are needed,  Change F to FT.
 


