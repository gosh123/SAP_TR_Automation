# SAP_TR_Automation

 This is a windows batch script for Moving sap change request manually through OS in a particuller order.
 To use this script Place these both files in your SAP server and change the extention of script file to .bat
 now simpley edit your transport profile path in the script and save it as script.bat


 Transport Profile Path Example = \\<hostname>\sapmnt\trans\bin\TP_DOMAIN_<SID>.PFL (specific Example)

 U128 is used in the script for ignoring component version


 for moving TR just put TR numbers in the TR_number file and save them (make sure to write one TR per one line)
 Excute the bat file this script will first add the data co file in your buffer then move the TR

 You will get the respective RC in the command prompt.
 
 # Challenge
 
 This Script has one challenge where if you are togather moving 10 TR's and the 5th TR got RC 12/8 it will keep moving other TR as well this creates a problem if TR's are dependent on each other and movement process need to be stopped if RC 12 comes.
 
 # Solution
 
 Though i am working on solution for the problem, Try moving TR's in small chunks of 5-6 at once so that even if you get a RC 12 or 8 rest TR we can re import easyly.


 Thanks,
 Manish Joshi
