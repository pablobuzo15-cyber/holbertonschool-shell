## Scripts Description

- **0-iam_betty:** switches the current user to the user `betty`.
- **1-who_am_i:** prints the effective username of the current user.
- **2-groups:** prints all the groups the current user is part of.
- **3-new_owner:** changes the owner of the file `hello` to the user `betty`.
- **4-empty:** creates an empty file called `hello`.
- **5-execute:** adds execute permission to the owner of the file `hello`.
- **6-multiple_permissions:** adds execute permission to the owner and the group owner, and read permission to others, for the file `hello`.
- **7-everybody:** adds execute permission to the owner, group owner, and others for the file `hello`.
- **8-James_Bond:** sets the permissions of the file `hello` so that the owner and group have no permissions, and others have all permissions.
- **9-John_Doe:** sets the mode of the file `hello` to `-rwxr-x-wx`.
- **10-mirror_permissions:** sets the mode of the file `hello` to be the same as the file `olleh`.
- **11-directories_permissions:** adds execute permission to all subdirectories of the current directory for all users (owner, group, others). Regular files are not changed.
- **12-directory_permissions:** creates a directory called `my_dir` with permissions `751`.
- **13-change_group:** changes the group owner of the file `hello` to `school`.
- **14-change_owner_and_group:** changes the owner to `vincent` and the group owner to `staff` for all files and directories in the current working directory.
- **15-symbolic_link_permissions:** changes the owner and group owner of the symbolic link `_hello` to `vincent` and `staff` respectively.
- **16-if_only:** changes the owner of the file `hello` to `vincent` only if it is currently owned by `guillaume`.
