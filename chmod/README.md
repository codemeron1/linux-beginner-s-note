## How do I change directory permissions in Linux?
To change directory permissions in Linux, use the following:
* **chmod +rwx **filename to add permissions
* **chmod -rwx **directoryname to remove permissions. 
* **chmod +x** filename to allow executable permissions.
* **chmod -wx** filename to take out write and executable permissions.

*Note that “r” is for read, “w” is for write, and “x” is for execute. *

![](https://www.pluralsight.com/content/dam/pluralsight2/b2c-blog-files/seo-refresh/linux-file-permissions/Linux-File-Permissions-1.webp)

![](https://www.pluralsight.com/content/dam/pluralsight2/b2c-blog-files/seo-refresh/linux-file-permissions/Linux-File-Permissions-2.webp)

## What are the three permission groups?
There are three options for permission groups available to you in Linux. These are

- **owners**: these permissions will only apply to owners and will not affect other groups.
- **groups**: you can assign a group of users specific permissions, which will only impact users within the group.
- **all users**: these permissions will apply to all users, and as a result, they present the greatest security risk and should be assigned with caution.

# What are the three kinds of file permissions in Linux?
There are three kinds of file permissions in Linux:

- **Read** (r): Allows a user or group to view a file.
- **Write** (w): Permits the user to write or modify a file or directory.
- **Execute** (x): A user or grup with execute permissions can execute a file or view a directory.

**How to Change Directory Permissions in Linux for the Group Owners and Others**
The command for changing directory permissions for group owners is similar, but add a “g” for group or “o” for users:

- chmod g+w filename
- chmod g-wx filename
- chmod o+w filename
- chmod o-rwx foldername

To change directory permissions for everyone, use “u” for users, “g” for group, “o” for others, and “ugo” or “a” (for all).

- **chmod ugo+rwx **foldername to give read, write, and execute to everyone.
- **chmod a=r ** foldername to give only read permission for everyone.

Reference:
[https://www.pluralsight.com/blog/it-ops/linux-file-permissions](https://www.pluralsight.com/blog/it-ops/linux-file-permissions)


