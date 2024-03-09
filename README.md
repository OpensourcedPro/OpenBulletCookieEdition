# OpenBullet Cookie Edition

- - - -

OpenBullet Cookie Edition is a webtesting suite that allows to perform requests towards a target webapp and offers a lot of tools to work with the results. This software can be used for **scraping** and **parsing data**, automated **pentesting**, unit testing through **selenium** and much more.

**IMPORTANT!** Performing (D)DoS attacks or credential stuffing on sites you do not own (or you do not have permission to test) is **illegal!** The developer will not be held responsible for improper use of this software.

![Runner](https://i.imgur.com/cHt4VFj.png)

# How to build
0. Make sure you have installed the .NET framework (dev) 4.7.2.
1. **Clone this repository** and open the solution file with Visual Studio.
2. Switch to **Release** mode for a much cleaner output.
3. **Build** the solution (Visual Studio will fetch all the missing nuget packages).
4. You can find the executables inside the folders OpenBullet/bin/Release and OpenBulletCLI/bin/Release.
5. 
- - - -

# OpenBullet Cookie Edition Building Configs Guide

- - - -

**# What can this bullet do?**

It is needed to work with your cookies.

In the Cookies section you can add a folder with logs, the bullet will automatically find all the cookies inside all the logs.

When creating a config, you must select the config type: CE (Cookie Edition)

![image](https://github.com/OpensourcedPro/OpenBulletCookieEdition/assets/139492588/671bdc02-248b-4d21-a05e-f021ec08e158)

CookieEdition - the config will work with Cookies files
Default - a normal standard config that works with Combolists and Wordlists


After you have created a config with the CookieEdition type, you definitely need to add a block that works with cookies. It's called Cookie Container.

![image](https://github.com/OpensourcedPro/OpenBulletCookieEdition/assets/139492588/29b6ef44-9198-4ef5-853b-6a655785e1d7)

# **What is Cookie Container?**

![image](https://github.com/OpensourcedPro/OpenBulletCookieEdition/assets/139492588/c736ecf5-be69-4a23-881c-806573a6cdf7)

Variable Name is the name of the variable in which the cookie will be placed and in the future you will be able to interact with it.

Input string - the string in which you place the path to the cookie file. To do this, we need to add the <COOKIEPATH> variable there
<COOKIEPATH> is a variable that stores a link to the path to the cookie file.

![image](https://github.com/OpensourcedPro/OpenBulletCookieEdition/assets/139492588/8d560027-84f6-4e50-aaff-2e96b23b9216)

Domain is a required field to fill out if you want everything to work correctly. This is the domain by which cookies will be searched in the cookie file.

Save netscape? - if this option is active, then the variable (which you do not see and do not set) <COOKIENETSCAPE> is filled with an unprocessed cookie in the Netscape format, which goes there directly from the log. This option is needed if you want to save valid cookies.



Let's move on.
#**How to debug this config?**

It is necessary to specify the CE format instead of Default and then specify the path to the file with cookies.

![image](https://github.com/OpensourcedPro/OpenBulletCookieEdition/assets/139492588/a90ced9b-0021-4120-86e6-70659373cb2a)
![030924](https://github.com/OpensourcedPro/OpenBulletCookieEdition/assets/139492588/83d1a0b6-0d0b-424a-943d-4dc4178888c8)
