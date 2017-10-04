# proxy_pac
This PAC allows users to visit Chinese websites via chinaproxy and oversea websites via overseaproxy. 

You just need to config the following variables:

var chinaproxy ='DIRECT'; //for visiting Chinese websites

var overseaproxy ='SOCKS5 1.2.3.4:5000;SOCKS 1.2.3.4:5000;DIRECT'; //for visiting oversea websites

* 'DIRECT' means connecting directly
* For SOCKS5 proxy, you need to add SOCKS to support iOS (with same address), for example 'SOCKS5 1.2.3.4:5000;SOCKS 1.2.3.4:5000;'.
