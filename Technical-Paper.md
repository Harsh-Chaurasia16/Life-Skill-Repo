# Content Delivery Network

A content delivery network (CDN) is a geographically distributed network of proxy servers and their data centres. 

The goal is to provide high availability and performance ("speed") by distributing the service spatially relative to end users. 

CDNs have grown in loading Internet content, including :
* web objects (text, graphics and scripts)
* Downloadable objects (media files, software, documents)
* Applications (e-commerce, portals)
* Live streaming media
* On-demand streaming media 
* Social media sites.
![CDN](https://upload.wikimedia.org/wikipedia/commons/thumb/2/26/NCDN_-_CDN.svg/800px-NCDN_-_CDN.svg.png)
 
 (Left) Single server distribution (Right) CDN scheme of distribution

## Technology

CDN nodes are usually deployed in multiple locations, often over multiple Internet backbones. Benefits include:- 
* reducing bandwidth costs,
* improving page load times, 
* increasing the global availability of content. 

The number of nodes and servers making up a CDN varies, depending on the architecture
1. some reach thousands of nodes with tens of thousands of servers on many remote points of presence (PoPs). 
2. Others build a global network and have a small number of geographical PoPs.

Requests for content are typically algorithmically directed to nodes that are optimal in some way. When optimizing for performance, locations that are best for serving content to the user are chosen based on:-
* The fewest hops,
* The lowest number of network seconds away from the requesting client,
* the highest availability in terms of server performance (both current and historical).

When optimizing for cost, locations that are the least expensive may be chosen instead. In an optimal scenario, these two goals tend to align, as edge servers that are close to the end user at the edge of the network may have an advantage in performance or cost. 

## Benefits of using CDN

### Improving website load times
* By using a nearby CDN server visitors experience faster page loading times. 
* As visitors are more inclined to click away from a slow-loading site, a CDN can reduce bounce rates and increase the amount of time that people spend on the site. 

### Reducing bandwidth costs 
* Through caching and other optimizations, CDNs are able to reduce the amount of data an origin server must provide, thus reducing hosting costs for website owners.
    
### Increasing content availability and redundancy
* A CDN can handle more traffic and withstand hardware failure better than many origin servers.

### Improving website security
* A CDN may improve security by:  
  * Providing DDoS mitigation
  * Improvements to security certificates and
  * Other optimizations.

# Refrences

1. https://en.wikipedia.org/wiki/Content_delivery_network
2. https://www.cloudflare.com/learning/cdn/what-is-a-cdn/
