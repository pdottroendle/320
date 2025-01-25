# 320
Bellevue College Software BAS 2025

=================================================\
WEEK 3\
WINTER TERM 2025\
BAS Programming - DEV 320 - Cumulative\
Timesheet\
Journal\
Retrospective\
=================================================\
Timesheet\
- 1/20/25 2PM to 6PM
Canvas + Online Class = Total
2 hours + 1'50 hours = 2'50
time spend on: preparing the online meeting, setting up github and CMDR
cummulative total = 4'50\
- 1/22/25 2PM to 6PM
Canvas + Online Class = Total
4 hours + 1'40 hours = 5'40
time spend on: creating the repositary for the preliminary webpage publication
cummulative total = 9'30\
-------------------------------------------------\
Journal \
\
============================\
explorations CMDER with sudo:\
Open Settings: Press Win + I to open the Settings app.
Go to System: In the Settings app, click on "System" in the left-hand menu.
For Developers: Scroll down and click on "For Developers."
Enable Sudo: Find the "Enable Sudo" option and turn it on\
\
explorations CMDER with iostat and other commands:\
F:\BC2025\DEV320\cmder\
λ sudo apt-get install sysstat\
Command not found <<< ?????\
\
λ choco version\
2.4.1\
SET "PATH=%PATH%;C:\ProgramData\chocolatey\bin"\
refreshenv\
winget install sysstat\
choco install sysstat\
\
wont work\
\
df - Report disk space usage of filesystems.\
 the package mF:\BC2025\DEV320\cmder\
Please see httλ df\
 assistance.  Filesystem                                    1K-blocks      Used Available Use% Mounted on\
C:                                            123754052 114457796   9296256  93% /c\
F:/BC2025/DEV320/cmder/vendor/git-for-windows   7846416   1785996   6060420  23% /\
D:                                            976760828 918539936  58220892  95% /d\
\
du - Estimate file space usage.\
F:\BC2025\DEV320\cmder\
λ du\
4       ./bin\
4       ./config/profile.d \
..\
\
ps aux - Report a snapshot of current processes.\
F:\BC2025\DEV320\cmder\
λ ps aux\
      PID    PPID    PGID     WINPID   TTY         UID    STIME COMMAND\
     1583       1    1583       2944  cons0     197108 19:50:24 /usr/bin/ps\
\
netstat - Print network connections, routing tables, interface statistics, masquerade connections, and multicast memberships.\
>netstat \
provides usefull IP adresses linked to processes and ports\
  TCP    172.29.0.219:58019     137.221.105.232:https  ESTABLISHED\
\
ifconfig - Display or configure network interfaces.\
\
Clink v1.7.7 is available.\
  \
================================================================================\
Verify the installation of .NET9 after successfully installing Visual Studio coder\
\
F:\BC2025\DEV320\cmder\
λ dotnet --info\
.NET SDK:\
 Version:           9.0.102\
 Commit:            cb83cd4923\
 Workload version:  9.0.100-manifests.43af17c7\
 MSBuild version:   17.12.18+ed8c6aec5\
\
Runtime Environment:\
 OS Name:     Windows\
 OS Version:  10.0.26100\
 OS Platform: Windows\
 RID:         win-x64\
 Base Path:   C:\Program Files\dotnet\sdk\9.0.102\ \
\
.NET workloads installed:\
There are no installed workloads to display.\
Configured to use loose manifests when installing new manifests.\
\
Host:\
  Version:      9.0.1\
  Architecture: x64\
  Commit:       c8acea2262\
\
.NET SDKs installed:\
  9.0.102 [C:\Program Files\dotnet\sdk]\
\
.NET runtimes installed:\
  Microsoft.AspNetCore.App 9.0.1 [C:\Program Files\dotnet\shared\Microsoft.AspNetCore.App]\
  Microsoft.NETCore.App 9.0.1 [C:\Program Files\dotnet\shared\Microsoft.NETCore.App]\
  Microsoft.WindowsDesktop.App 9.0.1 [C:\Program Files\dotnet\shared\Microsoft.WindowsDesktop.App]\
\
Other architectures found:\
  None\
\
Environment variables:\
  Not set\
\
global.json file:\
  Not found\
\
Learn more:\
  https://aka.ms/dotnet/info\
\
Download .NET:\
  https://aka.ms/dotnet/download\
\
======================= \
commands for the apache\
\
dotnet --info\
\
Installing the Apache Server:\
>sudo apt-get update\
>lsb_release –a\
>sudo apt–get install apache2\
>sudo systemctl status apache2\
>sudo systemctl start apache2\
>sudo systemctl stop apache2\
>sudo systemctl restart apache2\
\
Permissions\
sudo chown –R xlyns@xlyns.com /var/www/html\
\
Enter http://\
Apache\
\
----------------------------------------------\
Retrospective\

Before completing the assignments this week, I thought the layout was not looking proficient and wondered about how to make colums in rows.
After completing this week's assignments, I now think the container fluid is amzing to help do that for the different mobiles devices and formats too.
It was the Bootstrap concept using the id and classes that changed my thinking, as now the layout is obkject oriented and less repeated commands are needed.

adding the files and working on them was straightforwards using apache and the linux commands for githut and the server chosen

Test\
Shall = required not optional\
Should = optional \

>> Systems Test >> Intergration Test >> Unit Tests  >> Code V - Model \
 Units tests methodology covered in class\
\

=========== \
File Header \
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8"> \
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no"> \
    <title>About Peta Troendle</title> \
    <meta name="description" content="CSI443 Web site.  Text here shows up in the description listed in search engine results."> \
    <meta name="keywords" content="HTML,CSS,XML,JavaScript"> \
    <meta name="author" content="Peta Troendle"> \
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous"> \
	<link rel="stylesheet" href="../css/style.css"> \
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script> \
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script> \
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>  \

=================================================\
WEEK 2\
WINTER TERM 2025\
BAS Programming - DEV 320 - Cumulative\
Timesheet\
Journal\
Retrospective\
=================================================\
Timesheet\
- 1/14/25 2PM to 6PM
Canvas + Online Class = Total
1 hours + 1'50 hours = 2'50
time spend on: preparing the online meeting, setting up github and CMDR
cummulative total = 3'50\
- 1/16/25 2PM to 6PM
Canvas + Online Class = Total
3 hours + 1'40 hours = 4'40
time spend on: creating the repositary for the preliminary webpage publication
cummulative total = 7'30\
-------------------------------------------------\
Journal\
\
>>git init\
>>git add *\
>>git status\
git add README .md\
>>git commit -m "first commit"\
>>git branch -M main\
>>git remote add origin https://github.com/ptroendle/nnnnn.git\
>>git push -u origin main\
if fails use the drag and drop and commit\
settings\
pages branch\
gh-pages\
settings pages reload\
\
----------------------------------------------\
Retrospective\
The access was restaured yesterday Jan 21 after 4 days in the dark (Jan 17 +) - use the tracking systme - resolved\
The Fax numbers published by BC are all false, all fax equipments where removed by IT 4 weeks ago - used UPS - resolved\
The N252 audio is defectuous and other issues observed [comments n.a.]- using own laptop installed .NET9 - resolved\
The access to Zoom is now facilitated by manual distribution of the invites as the generic link advertised dont work even after a successfull SSO and Registration process - resolved\
The Google Cloud decided to block all my accounts flagging the Bellevue College for some reason - resolved\
\
Web Application Resource Research is adding a page (linked to it)\
with research results and links in the new page\
fixed issues like the bootstrap, use the online bootstrap.min.css\
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>\
\
Managed to get apache servers, webpages online in Git and in the Server (used my own instead of the Google as they are still blocking my credit institution he US Bank).\
\
=================================================\
WEEK 1\
WINTER TERM 2025\
BAS Programming - DEV 320 - Cumulative\
Timesheet\
Journal\
Retrospective\
=================================================\
Timesheet\
- 1/7/25 2PM to 6PM
Canvas + Online Class = Total
2 hours + 1'50 hours = 3'50
time spend on: preparing the online meeting, setting up github and CMDR
cummulative total = 3'50 \
- 1/9/25 2PM to 6PM
Canvas + Online Class = Total
2 hours + 1'50 hours = 3'50
time spend on: creating the repositary for the preliminary webpage publication
cummulative total = 7'40 \
------------------------------------------------- \
Journal \
>ls -la \
>cd.. \
>pwd \
>cp \
>mv \
>mkdir \
>rmdir \
>help \
3 Layers for the web: \
Backend data (MongoDb, mySQL, ..) \
Middleware stacks (C#, PHP, ..) \
Frontend <Markups (HTML, ..) \
different languages for applications middleware: \
C++ \
pl perl \
php \
Java \
C# .NET pseudo Java \
AJAX 1989 >> html asy Js xml Web2 XML \
for databases: \
MongoDB MariaDB MySQL MSQL SQL \
stored procedure >> JSON >> HTTP header \
and frontend: \
to create the html file: \
() are used instead of <> that cause a problem in the markup: \
(!DOCTYPE html) \
(head)(/head) \
(body)(/body) \ \
(/html) \
 \
placing the web files on a Git repo: \
C:\Users\p.troendle\Desktop\320 \
ls -la \
README.md \
>>git init \
>>git add * \
>>git status \
git add README .md \
>>git commit -m "first commit" \
>>git branch -M main \
>>git remote add origin https://github.com/ptroendle/nnnnn.git \
>>git push -u origin main \
if fails use the drag and drop and commit \
settings \
pages branch \
gh-pages \
settings pages reload \
created the web page and link \
I used the wrong repo to load deleted the project in github in the dangerzone and \
recreated from scratch: \
echo "# DEV320" >> README.md \
git init \
git add README.md \
git commit -m "first commit" \
git branch -M main \
git remote add origin https://github.com/pdottroendle/DEV320.git \
git push -u origin main \
v12.13.0 nodes was installed chaecked on CMDR \
It worked, published my first webpage in 2025! \
https://validator.w3.org/ is helpfull for checking the markup \
https://www.w3resource.com/linux-system-administration/linux-commands- \
introduction.php for linux data handling and types \
my favorite link: https://nodejs.org/en/download/ \
it allows me to create a stack on my laptop and run a server from there (I tried it \
in the Starbucks and ran a server for a couple minutes from there using nodes) \
---------------------------------------------- \
Retrospective \
What commands did you use in the terminal for linux, node, etc. \
After installing CMDR and Nodes I used ls -la to have a directory view and cd or \
cd.. to navigate \
>ls -la \
>cd.. \
>pwd \
>cp \
>mv \
>mkdir \
>rmdir \
>help \
What helpful code snippets, practices, helpful tips, etc. that you want to refer \
back to easily: \
the node installation ht \

