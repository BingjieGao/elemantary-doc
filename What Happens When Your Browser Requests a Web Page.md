#### The General steps of a Browser requesting a Web Page
1. DNS Lookup
2. Browser sends a HTTP request to server
3. Server responds back with responses
4. Browser Begins to render HTML

#### DNS Lookup
The human-readable domain name is to be checked and get the IP via DNS lookup, the steps taken to get the IP address are:
1. local host file validation - ```/etc/hosts``` file holds the domain and IP address
2. Browser cache - cache stored in browser is checked
3. Operating system - cache stored local is checked, also in host file
4. Local DNS server check
5. Local DNS server will send the 'name resolution' request to the 13 root DNS server or

* The recursive query is between a DNS client and its local DNS server.
* The iterative query is between a local DNS server and other DNS servers
