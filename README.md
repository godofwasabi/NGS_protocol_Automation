# NGS_protocol_Automation
This is an attempt to automate Rödelsperger's NGS protocol.
Automation_v1_2.sh
	Written by Erick (02/05/2021)
--------------------------------------------
Hello to "v1_2".

The current protocol:

"A simplified workflow for the analysis of whole-genome sequencing data from mutant lines
		with an application to the nematode Pristionchus pacificus"

 			written by Christian Rödelsperger.

Uses BWA, samtools, and bcftools which are tools or packages that can be readily downloaded
and installed. These tools are "linux/Mac based" to put it simply.

Windows users need to download an "emulator" of linux terminal such as "ubuntu 20.04" from 
sources such as the Microsoft store. (I use ubuntu 20.04.)
---------------------------------------------
Installing Tools

For Windows 10:
1.	Install “ubuntu 20.04 LTS” (free) from the Microsoft store
2.	Once installed correctly
3.	Open windows command shell and type “bash”; it may take a few moments for first time running.
4.	$ sudo apt-get install bwa
5.	$ sudo apt-get install samtools
6.	$ sudo apt-get install bcftools
7.	You are now free to continue.

For Mac users:
1.	Open terminal/console
2.	$ brew install bwa
3.	$ brew install samtools
4.	$ brew install bcftools
5.	You are now free to continue.
-----------------------------------------------
Some computer systems may require admin or even root permissions in order to run the bash script.

The simplest way ensure the script does not fail mid-way:

>sudo -i sudo -s

Bash script can now be ran with full permissions.

------------------------------------------------
Initiating the bash script

>./Automation_v1_2.sh
