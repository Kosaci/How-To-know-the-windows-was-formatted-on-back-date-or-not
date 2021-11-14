# How-To-know-the-windows-was-formatted-on-back-date-or-not
 
Here I found Two cases 
1. Update The windows.
2. Format The windows.


In our First Case We can check The Simw Windows file Creation Date. Those files are system.ini,Win.ini.
Follow My steps and Check The Creation time
1. Open The powershell.
2. And type The command (Get-Item C:\Windows\system.ini).CreationTime
3. It gives The Creation Time.
4. Then you know Windows is updated from previous version.

But This Case is failes when Windows is formated in back date Bcoz it gives same  Date of Back date when Windows is formatted.

Dont worry we Have some theoretical approach For this on case 2.

Every one uses New latest updated burnning iso image for installing windows.

On every Windows we can see the build number like eg. (OS Build 14393.1884) by typing winver

Just google the build number we can find the release date of the particular build number.

So we can see the os installation date by typing systeminfo from cmd then you got orginal install date.

The match both you can find the pc is formatted in back date or not.
