# Group Project MSSE 642 Sping 1 2026

## Summary
- Replace the short papers on security vulnerability analysis with coding assignments using AI tools for help.   See the class video for a demo.  
- Project 1: Do this as is.  Set up a Penetration Testing Lab on your personal computer.  Everyone does this. If you have problems you can get help from the class. 
- Project 2:  Do this individually or as a group.  Put all of the group members on the title page of your paper.  You can use AI.  
- Project 3 and Project 4:   Perform penetration testing on an app that you code.  Divide your work.  One part of the team might focus on writing the code, another part may focus on containerizing the app so you can run it anywhere, another on penetration testing, etc.  
- Final Presentation: you will present what you have done either live in class or in a video.  


## Assignments that will adapted for the Group Project 

| ASSIGNMENT | DUE | SUMMARY |
|---|---|---|
| Security Vulnerability Analysis | Each Week | This was useful at one time, but in a software engineering program, but it would be an ideal opportunity to try to code a small app that can be tested for this vulnerability to interact with AI tools to ensure that this vulnerability does not exist.<br><br>**New Project:**<br>Code and app or demo that demonstrates with vulnerabilities |
| Project 1 | A flexible end of Week 2 | Work as a group to set up your own local Pen Testing environment. Deploy 2 VMs, one Kali Linux and another with a vulnerable app that you code or test. |
| Project 2 | Week 4 | Work as a group or in small groups to perform a Threat Analysis following the existing instructions. |
| Project 3 | Week 6 | Work through the Sing book to test more or more applications that you code |
| Project 4 | Week 8 | Continue with project 3 |
| Final Presentation | Week 7 and Week 8 | To replace a take home exam. Present the results of the three projects and the Security Vulnerability Analysis exercises. You can do this in class or if you can't make it to class you can make a video (5 minutes) with a Power Point Presentation. |

## How to submit your work

- You will submit all of your assignments in Git Hub as documents in Markdown format.  
- You can refer to the Markdown Cheat Sheet and this project description for examples on how to create markdown (see below for link and details). 

### Steps

- If you don't have one already, set up a Git Hub Account.  You can use your personal email or your Regis email, but be aware that switching Git Hub accounts can be tricky since things like passwords can be stored locally in a password manager and can conflict when you try to switch accounts.   I recommend you use only one Git Hub account in your environment.   

- Create a new repository called MSSE642-2026Spring

#### Figure 1
![alt text](images/figure1.png)


- Clone the repo on your local environment and integrate with git and your IDE.   If you are on Windows, you might want to install Git Bash for Windows.  

- Decide of you want to access your repo via ssh or http.  If you access via ssh, you will need to configure RSA keys.  If you access via https, you will use a password, which is often stored in a Password Manager.  This is configured when you set it up, and as long as you don't switch Git Hub accounts, you should not run into any issues.   

#### Figure 2
![alt text](images/figure2.png)

- The following screen shot shows how you can integrate this flow into Visual Studio Code using Windows Subsystem for Linux and Terminal Window opened in Visual Studio Code.  

- You can set up your development environment in any way you want as long as your IDE of choice is configure to use Git Hub.  

#### Figure 3
![alt text](images/figure3.png)

Example Commands

```bash
rhuser@DellXPS:~/github$ mkdir MSSE642-2026Spring
rhuser@DellXPS:~/github$ cd MSSE642-2026Spring/

rhuser@DellXPS:~/github/MSSE642-2026Spring$ echo "# MSSE642-2026Spring" >> README.md

rhuser@DellXPS:~/github/MSSE642-2026Spring$ git init
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint:
hint:   git config --global init.defaultBranch <name>
hint:
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint:
hint:   git branch -m <name>
hint:
hint: Disable this message with "git config set advice.defaultBranchName false"
Initialized empty Git repository in /home/rhuser/github/MSSE642-2026Spring/.git/
rhuser@DellXPS:~/github/MSSE642-2026Spring$ git add *
rhuser@DellXPS:~/github/MSSE642-2026Spring$ git branch -M main
rhuser@DellXPS:~/github/MSSE642-2026Spring$ git branch
rhuser@DellXPS:~/github/MSSE642-2026Spring$ git commit -m "First commit"
[main (root-commit) ed616b6] First commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md


rhuser@DellXPS:~/github/MSSE642-2026Spring$ git remote add origin git@github.com:programmingkitchen/MSSE642-2026Spring.git

rhuser@DellXPS:~/github/MSSE642-2026Spring$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 236 bytes | 236.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To github.com:programmingkitchen/MSSE642-2026Spring.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
```

- I will put things in my repo.  It's public.  You can clone it on your PC. 

[MSSE642-2026Spring on GitHub](https://github.com/programmingkitchen/MSSE642-2026Spring.git)

#### Figure 4
![alt text](images/figure4.png)

- Here's an example of how you can use your IDE (in this case Visual Studio Code) in agent mode to create a Markdown Cheatsheet. 
- You can then push this to your GitHub Repo from your IDE.   
- You can find this Markdown cheatsheet in my repo, or you can create your own using GitHub Copilot.   
- You have the option to keep or undo changes. 

#### Figure 5
![alt text](images/figure5.png)

- After you make the changes, you can stage, commit, and sync

#### Figure 6
![alt text](images/figure6.png)

#### Figure 7
![alt text](images/figure7.png)

#### Figure 8
![alt text](images/figure8.png)

- When submitting your assignments, follow the directory structure outlined here:

#### Figure 9
![alt text](images/figure9.png)

- Going forward, refer to the document in the GitHub repo (above) for the most current version.  