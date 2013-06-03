Federation Node
===============
             
The Intention
-------------
Bring together the best of the [personal cloud](https://github.com/airships/zephyr/wiki/Personal-Clouds), 
[federated social web](http://en.wikipedia.org/wiki/Distributed_social_network), 
and [indieweb/POSSE](http://indiewebcamp.com/POSSE) protocols, platforms, and applications, 
in an easily deployable server package that can be applied both to standard linux cloud servers 
and also to sub-hundred dollar personal servers such as the currently popular Raspberry Pi.

Server Roles
------------
- _home server_: large file storage, remote access 
  (this may be a low-cost plug computer connected to an external hard drive)
- _web host_: public and federation http server                            
  (A full OpenStack or similar instance with root access)
                               
Candidate Components
--------------------
Here are some of the components we may include.  
To contribute, please fork this document.  
Pull requests are welcome.

### Publish HTML
- apache or other standard web servers

### Publish Activity Streams
- [pump.io](http://pump.io/)

### Sync
- [camlistore](http://camlistore.org/)
- rsync

### Convert markdown to html
- [jekyll](http://jekyllrb.com/)
- [gist.io](https://github.com/idan/gistio)

### Protocols
- [activitystrea.ms](http://activitystrea.ms/)
- [tent.io](https://tent.io/)

### Bonus: cryptographically verifiable history
- [Git](http://git-scm.com/)
- [bitcoin-style block chains](https://www.khanacademy.org/science/core-finance/money-and-banking/bitcoin/v/bitcoin-transaction-block-chains)


Getting a Pi
------------

Two decent Amazon shopping list, current as of May 2013: 
- <http://www.amazon.com/lm/R1W0G1BRR6JQQH>
- <http://www.amazon.com/lm/RA6EX6ZYSH0UN>
