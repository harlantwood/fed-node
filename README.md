federated-pi 
============
             
The Intention
-------------
Bring together the best of the [personal cloud](https://github.com/airships/zephyr/wiki/Personal-Clouds), 
[federated social web](http://en.wikipedia.org/wiki/Distributed_social_network), and [indieweb/POSSE](http://indiewebcamp.com/POSSE) protocols, platforms, and applications, 
all on sub-hundred dollar personal servers.

The means
---------
Raspberry Pi personal server clubs (a.k.a. federations, therefore _federated-pi_) with install/hack fests around some of the components listed below.  Or better! -- please remix and upgrade these ideas.


Proposed roles for your devices and services
--------------------------------------------
- _your current primary device_: creation 
- _federated-pi_: home backup, sync, large file storage
- _web host_: content distribution and caching layer
                               
Candidate Components
--------------------

Here are some of the components we may include.
Don't be daunted!  We will start small, get things up and running fast, and add components as needed.
This should be entirely driven by actual needs and desires, eg sharing files, publishing, etc.

## Publish HTML
- apache or other standard web servers

## Publish Activity Streams
- [pump.io](http://pump.io/)

## Sync
- [camlistore](http://camlistore.org/)
- rsync

## Convert markdown to html
- [jekyll](http://jekyllrb.com/)
- [gist.io](https://github.com/idan/gistio)

## Protocols
- [activitystrea.ms](http://activitystrea.ms/)
- [tent.io](https://tent.io/)

## Bonus: cryptographically verifiable history
- [Git](http://git-scm.com/)
- [bitcoin-style block chains](https://www.khanacademy.org/science/core-finance/money-and-banking/bitcoin/v/bitcoin-transaction-block-chains)
