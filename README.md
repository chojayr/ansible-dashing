# Dashing (Handsome Dashboard) 

Playbook to install Dashing 


## Requirements

Dashing required Ruby version 1.9.x and other gems like bundler, rake etc.
also package like make, libv8-dev & nodejs


## Supported System

Tested and run on Ubuntu 12.04 32 & 64bit. patch for other server soon  


## Dependencies 

* Rbenv ( added rbenv.yml task to install rbenv )


## Role Variables

* ruby_version: 1.9.3-p484
* rbenv_root: /usr/local/rbenv


## Test

created test-dashing.yml to run and test ansible-dashing

- vagrant up 
- ansible-playbook site.yml -i hosts -vvvv

once done go to http://ipaddress:3030/sampletv


## License

BSD


## Author Info

[Luis R. Lavina Jr] - jrlavina07 [at] yahoo dot com dot ph
		    - http://github.com/chojayr

