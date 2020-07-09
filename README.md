Xeroizer 3 pre beta

### This repository will be deleted sometime after the official Xeroizer gem releases version 3. 
### You shouldn't use this repository or gem.

Forked from the official repository at [http://waynerobinson.github.com/xeroizer](http://waynerobinson.github.com/xeroizer).

Due to [an issue](https://github.com/rvm/rvm1-capistrano3/issues/80) in deploying gems via Capistrano using the rvm1-capistrano3 gem, I'm not able to reference a gem via the normal method of deploying a non-tagged release, e.g. 

`gem 'xeroizer', git: 'https://github.com/waynerobinson/xeroizer', ref: 'e654beaa4caa034266dc8bf9cb8a95914d439085'`

As a result, I'm setting up this gem so the rvm1-capistrano3 gem can reference it directly. Once Xeroizer version 3 is released I will be deleting this repository and reverting back to using the official repo.

====================

**Homepage**: 		[http://waynerobinson.github.com/xeroizer](http://waynerobinson.github.com/xeroizer)
**Git**: 					[git://github.com/waynerobinson/xeroizer.git](git://github.com/waynerobinson/xeroizer.git)
**Github**: 			[https://github.com/waynerobinson/xeroizer](https://github.com/waynerobinson/xeroizer)
**Author**: 			Wayne Robinson [http://www.wayne-robinson.com](http://www.wayne-robinson.com)
**Contributors**: See Contributors section below
**Copyright**:    2007-2013
**License**:      MIT License

### Contributors
Xeroizer was inspired by the https://github.com/tlconnor/xero_gateway gem created by Tim Connor
and Nik Wakelin and portions of the networking and authentication code are based completely off
this project. Copyright for these components remains held in the name of Tim Connor.
