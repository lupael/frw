# frw

This is a fork of [arch-lamp/freeradius-web-ui](https://github.com/arch-lamp/freeradius-web-ui) which
includes some changes like:
- PGSQL support
- PHP7 Compatibility
- SSHA Passwords
- Separate table for user accounts
- ...

## What is FreeRADIUS?

FreeRADIUS is an open source software used to authenticate users over a wide range of networks for different services. This is the most basic explanation I can think of and if you want to dig deep, please head over to:
http://freeradius.org/

FreeRadius is used to authenticate users for different services such as Wi-Fi networks, openVPN, LDAP, Active Directory etc.

## What is frw?

frw is used to manage the users and NAS clients on the FreeRadius server. You can add, delete, reset password of users from the web-ui. You can also add, delete and edit NAS clients. The whole interface is build using Metro-UI which uses PHP as a backend. This makes the whole UI very lightweight and lightning fast.

Database currently supported is Postgresql / MariaDB / MySQL.


# Screenshots
![Dashboard](/screenshots/1.png)

## Some advices that I ([denysvitali](https://github.com/denysvitali/)) don't agree with, but were in the original README

(TODO: put this in a more fashioned way and change the title)

NOTE: Before executing the setup script, please make sure to assign full permissions (777) to the directory named 'includes'. Permissions must not be recursive. After installation is complete, you can again switch the permissions to old one.
### FreeRADIUS Server Installation
To install FreeRADIUS Server on CentOS 6.x. the installation script is available at: https://github.com/arch-lamp/install-free-radius-server
