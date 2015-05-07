#Omega 4 Ruby Set Up For Yosemite OS X

#### Steps assume you are starting from scratch, but you may already have some dependencies.

1. Install Xcode Command Line Tools
	* To check if already installed run: `$ gcc` or `$ make`
	* If you don't have Xcode Command Line Tools you will then be prompted to install it.

2. [Download GPG Tools](https://gpgtools.org/)

3. [Download RVM](http://rvm.io/)
	* `$ gpg --keyserver hkp://keys.gnupg.net --recv-keys D39DC0E3`
		* Go to [http://rvm.io/](http://rvm.io/) if you want newest version of RVM.
	* `$ \curl -sSL https://get.rvm.io | bash -s stable`

4. Restart terminal.

5. Install RVM
	* `$ rvm install ruby-1.9.3-p551`
		* If running into issues run: `$ rvm install 1.9.3 --with-gcc=clang`

6. Set newly installed ruby version as default
	* `$ rvm --default use 1.9.3`

7. Install all the gems
	* Go into your custom Omega theme.
	* `$ bundle install`

