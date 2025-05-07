# Exam Structure and guide

## Metadata

**tag**- #resources/info
date - 2025-05-07

---
## Duration
- `23H45M` for exam
- `24H` for documentation of exam
## Exam Structure

- **3 stand-alone machines (60 points in total)**
    - 20 points per machine
        - 10 points for initial access
        - 10 points for privilege escalation
- **1 Active Directory (AD) set containing 3 machines (40 points in total)**
    - For the Active Directory exam set, learners will be provided with a username and password, simulating a breach scenario.
    - 10 points for machine #1
    - 10 points for machine #2
    - 20 points for machine #3
#### Point allocation 
- Order in which they are documented in submitted documentation
- Stand-alone machines 
	- points will be awarded for partial and complete administrative control of machine
- Machines might have some `set of objectives` that must be completed
- Must score `70/100` to `pass`
## Exam Requirements 
- **Document Requirements**
	- Write professional report 
	- Document all of your attacks including all `steps`, ``commands issued``, and `console output` in the form of penetration test report.
	- document should be thorough enough for a reader to follow steps and replicate the same
- **Exploit code**
	- Only modified exploit code needs to added as snippet otherwise give the URL of that code 
	- If the code is modified then include 
		- modified code
		- URL of original code
		- command used to generate shell code(if any)
		- Highlighted changes you have made
		- An explanation of why the changes were made
- **Exam proof**
	- provide proof of exploitation for each machine
	- submit the proof in control panel and **add the Screen Shot** of same in documentation, these can be the file names
		- local.txt
		- proof.txt
	- How to provide Screen shot?
		- Go to the `exact location` of the flag in `remote shell`
		- use `cat` or `type` to show the content of the file in `remote shell`
	- On windows you must have shell running with the permission of one of the following to receive full points
		- `System user`
		- `Administrator user`
		- `User with Administrator privilage`
	- for Linux for full marks
		- `root shell`
- **Control Panel submissions** 
	- contents of `local.txt` and `proof.txt` are required to be submitted in control panel of the exam before submitting the exam
- **Screenshot requirements**
	- Each `local.txt` and `proof.txt` screen shot must contain IP of the target machine using `ipconfig`, `ifconfig` or `ipaddr`
	- ![[proof-text.png]]
- **Exam Restrictions**
	- spoofing
	- commercial tools or services (Metasploit pro, Burp pro, etc.)
	- Automatic exploitation tools (`db_autopwn`, `browser_autopwn`, `SQLmap`, `SQLninja`, etc. )
	- Mass vulnerability scanners (Nessus, `NeXpose`,` OpenVas`, Canvas, Core Impact, SAINT, etc. )
	- AI chatbots (`OffSec KAI`, `ChatGpt`,`YouChat`, etc. )
	- Can search on Discord but not allowed to take help from others
	- Delete all the downloaded files from your local system that were used to compromise the machine 
- 