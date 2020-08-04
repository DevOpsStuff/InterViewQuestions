# What Happens when you Type Google.com?
  
  Most Common interview Question.
 
  Typing `google.com`... and Hit Enter.

     Is it a URL? 
     Now, let's turn into a properurl like. 
  
     Does this site prefer Https? yes
     now browser turns in to https://google.com. 

     Is the URL in the browser cache? 
     cache-control: max-age

     should the cached content be revalidated ?
     cache-control: must-revalidate

  ### DNS Lookup: Browser Cache
 
     Is the hostname in the brower's cache?
     Yes!  Let's use that IP address.
  
  ### DNS Lookup: OS Resolver
     
     Is the hostname in the operating system's cache?
     Yes ! Let's use that Ip address
     
     Check /etc/hosts and resolve it. 

  ### DNS RECORD TYPES

      * A and AAAA are address records: mapping from name to IP address
      * PTR is a reverse mapping from IP address to name
      * NS is a pointer to a name server
      * Other record types: SOA,CNAME,MX,TXT

  - Send the DNS Request
    
   [More Info on DNS queries](https://github.com/DevOpsStuff/Networking/blob/master/DNS.md)


 ### Next TCP Three way handshake happens.

  ![TCPHANDSHAKE](https://cdncontribute.geeksforgeeks.org/wp-content/uploads/TCP-connection-1.png)
  
  More info: [HandshakeTCP](https://www.geeksforgeeks.org/computer-network-tcp-3-way-handshake-process/)
