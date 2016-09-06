# SAP_TR_Automation

 This is a windows batch script for Moving sap change request manually through OS in a particuller order.
 To use this script Place these both files in your SAP server and change the extention of script file to .bat
 now simpley edit your transport profile path in the script and save it as script.bat


 Transport Profile Path Example = \\<hostname>\sapmnt\trans\bin\TP_DOMAIN_<SID>.PFL (specific Example)

 U128 is used in the script for ignoring component version


 for moving TR just put TR numbers in the TR_number file and save them (make sure to write one TR per one line)
 Excute the bat file this script will first add the data co file in your buffer then move the TR

 You will get the respective RC in the command prompt.


 Thanks,
 Manish Joshi
