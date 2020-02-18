# PowerShell-SDET-Assessment

Question 1
An automation script written in powershell scripting language and running on a windows OS machine, is being worked on by a 
dev team. The main function of the script is:
	To SILENTLY install a text editor, notepad++, on a windows machine.
There are two main scripts handling this functionality:
1. MainScript.ps1 Main powershell script
2. InstallTextEditor.psm1 which has a module used by the main script

After a series of commits done by some of the team members, the automation script is no longer functioning as expected. 
You are tasked with analysing the provided code for the two scripts and provide a working solution that is able to SILENTLY
install the text editor. 

NB:SILENT INSTALLATION MEANS THAT THERE IS NO HUMAN INTERVENTION AFTER THE SCRIPT HAS BEEN EXECUTED.

Question 2
The dev team after fixing the automation script realised that the script had not handled the following use cases of the automation
script.
1. How to handle failed installation
2. How to log the events being handled by the automation script
3. How to ensure validity of data eg paths, .exe files throughout the execution of the script

Provide a brief description of how you would handle this scenario and then implement the solution in the automation script.
