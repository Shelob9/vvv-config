Basic configuration for setting for adding a new site in [VVV](https://github.com/Varying-Vagrant-Vagrants/VVV/).

For more information on how to use this to create new sites, see [my article on using Vagrant in Torque](http://torquemag.io/getting-started-vagrant-local-development/).

### Instructions:
* In VVV's www directory, create a new folder and give it a name.
* Add and configure WordPress in that directory according to your personal taste
* Clone or copy this repo in that directory.
* In each file from this repo change "site" to whatever you called the parent directory.
* vagrant provision

You may or may not need to vagrant halt and vagrant up to get it to work.
