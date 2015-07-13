# Checker

Changelog
v1.0	First issue	10/07/2015	Michele Quattrone/Rodrigue Fokouop

This is the checker of the ROADEF/EURO challenge 2016 (version 1.0.0.0).

This archive contains:
- a Windows executable file (...\Challenge_Roadef_EURO_Ckecker_Version_1.1\bin\Release\IRP_Roadef_Challenge_Checker.exe).
- the source files associated (Challenge_Roadef_EURO_Ckecker_Version_1.1 folder)- visual studio 2012  or greater (https://msdn.microsoft.com/en-us/library/vstudio/dd831853(v=vs.110).aspx) is required on windows and mono (http://www.mono-project.com/) is required on linux.

To run it:
- unzip Challenge_Roadef_EURO_Ckecker_Version_1.1.zip  folder
- launch the executable "...\Challenge_Roadef_EURO_Ckecker_Version_1.1\bin\Release\IRP_Roadef_Challenge_Checker.exe" from a command line with two arguments:
	1) Path to the instance file (xml file)
	2) Path to the solution file as xml file (the xml file needs to respect the spec of solution file)


Example (replace with appropriate paths/filenames):

	$> ...\Challenge_Roadef_EURO_Ckecker_Version_1.1\bin\Release\IRP_Roadef_Challenge_Checker.exe "...\path\to\instance\myInstance.xml" "...\path\to\solution\mySolution.xml" (Linux) mono is required.

	C:\> ...\Challenge_Roadef_EURO_Ckecker_Version_1.1\bin\Release\IRP_Roadef_Challenge_Checker.exe "...\path\to\instance\myInstance.xml" "...\path\to\solution\mySolution.xml" (Windows)
