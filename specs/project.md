# My dev project

My-dev is the utility which allows users to get rid of
passwords in connections to their services, such as SSH,
Github, git etc.

## Main idea

This utility consist 2 parts, client and server.

On server side, you can store your passwords, usernames,
another key pairs.

For using client you have to install it on your PC(UNIX-like),
and you can try to log in.


## Usage

1. Install client on PC:
```
$ > pip install my-dev
```

2. Log in/Register in my-dev via:
```
$ > my init
```

3. Try to use, like:
```
$ > my ssh 192.168.0.2
$   This host not exist in DB. Do you want to add? (Y/n): y
$   Username for this host: root
$   Password:
$   Done!
$ > my ssh 192.168.0.2
$ [~] > 
```
