# useradd

Create a new user account.

sudo useradd devops
# passwd

Set or update a user's password.

sudo passwd devops
# userdel

Delete a user account.

sudo userdel devops
# groupadd

Create a new group.

sudo groupadd developers
# gpasswd

Manage group membership. Adding devops to developers group.

sudo gpasswd -a devops developers
# groupdel

Delete a group.

sudo groupdel developers
