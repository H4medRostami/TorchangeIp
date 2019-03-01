# TorchangeIp
Config Tor :

      sudo apt-get update
      sudo apt-get install tor
      sudo /etc/init.d/tor restart
      tor --hash-password <enter your password here>
      nano /etc/tor/torrc
  
      SOCKSPort 9050 comment and uncomment 9051 controller
      
      HashedControlPassword <your hashed passsword obtained earlier here>  uncomment
      
      CookieAuthentication 1 uncomment
