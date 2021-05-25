# PRTG-WinServiceCheck
An advanced PRTG Script for monitoring Windows Services that I created a couple of years ago.

You need to place the .ps1 file in the EXEXML folder of your PRTG probe server, and add this as a custom EXE XML sensor with AdvancedAutomaticServicesCheck.ps1 as the target. You can either turn on the 'Set placeholders as environment values' PRTG setting (recommended), or add the required parameters in the parameters feild.

This is my version adapted from the basic EXE one originally written by Stephan Linke at Paessler; see https://kb.paessler.com/en/topic/62319-how-do-i-monitor-all-services-on-a-server-set-to-automatic for the original.
