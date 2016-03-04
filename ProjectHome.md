# Motivation #
Traditionally U-Boot has worked with terminal applications such as minicom/hyperterminal/ckermit etc. However,

  * These applications dont work out fine when we think of automating these as part of scripts or the like.
  * Many corporations use a mixture of Operating Systems at work. Common applications functioning similarly accross host Operating Systems are sadly lacking.

With the bunch of utilities in this project, we hope to bridge these gaps. We can create wrappers on top of these utilities, allowing us to potentially have scripted interfaces or even GUI, or IDE integration!

# Hosting Notes #
OMAP-U-Boot-Utils is hosted at two places:
  * **Source Code hosting**: Git Hub http://github.com/nmenon/omap-u-boot-utils/
  * **Binaries and Documentation**: code.google.com - this site.

# Access Source Code #
Considering that most U-Boot and Linux kernel developers are git users, the source is hosted at github. There are two access paths:
  * http protocol - for folks behind restrictive firewalls: http://github.com/nmenon/omap-u-boot-utils.git
  * git protocol: git://github.com/nmenon/omap-u-boot-utils.git
To get a copy of the code, it is as simple as:
```
git-clone git/http link
```
**NOTE**:
  * Users with proxy need to remember to setup their http\_proxy variable. Here is more information: http://ubuntuforums.org/showthread.php?t=1575
  * More on using Git: http://github.com/guides/home


# Operating Systems Supported #
The targetted Operating Systems to be supported by this are:
  * Linux
  * Windows
  * Mac OS X
**NOTE**: Not all O/S are functioning at the moment for all applications. documentation has further information

# How to Discuss/ Send Patches for OMAP U-Boot Utils #
There is no specific mailing list setup at the moment - but send a patch to http://groups.google.com/group/beagleboard with subject OMAP-U-Boot-Utils and I will pick it up..

Coding style is Linux kernel coding style, and do run checkpatch.pl and Lindent to indent the file.. See http://lxr.linux.no/linux/Documentation/CodingStyle for more details

Happy Hunting..