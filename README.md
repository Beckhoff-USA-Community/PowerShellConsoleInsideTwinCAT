# About This Repository

How this project is cool?
Move files around, delete folders, set windows registeries, change network settings easily from TwinCAT via a powershell terminal. 

How easy is this to use?
Send the functionblock a string, or 1000 strings of powershell code via 1 method call. That's it.

What happens behind the hood?
Behind the sceens this program will copy your desired powershell code to a powershell file in windows. Then it creates a batch file. After the files are written, TwinCAT executes the batch file which then runs the powershell program with the correct policies. All this happens automaticlly so you can just focus on what powershell code you want it to execute. 


This sample is created by [Beckhoff Automation LLC.](https://www.beckhoff.com/en-us/), and is provided as-is under the Zero-Clause BSD license.

## Requirements

The following components must be installed to run sample code:

- [TE1000 TwinCAT 3 Engineering](https://www.beckhoff.com/en-en/products/automation/twincat/te1xxx-twincat-3-engineering/te1000.html) version 3.1.4024.0 or higher
- Windows 10 or newer. 
