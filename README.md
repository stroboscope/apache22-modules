# apache22-modules

Miscellaneous Modules for Apache 2.2 (and maybe 2.4), licensed under Apache License v2.0.

| module  | description | state |
| :------ | :---------- | :---- |
| myfixip | Fix "remote_ip" in HTTP/HTTPS ([PROXY protocol](http://www.haproxy.org/download/1.5/doc/proxy-protocol.txt), like ha-proxy and Amazon ELB) | stable |
| node    | Add "Node: hostname" to Request/Response Headers | stable |
| test    | Always response "OK\n" (For check Apache Health) | stable |
| random_header | Generate X-Random Header (Variable Length) | beta |
| auth_basic_check | Checks Constraints for Passwords in Auth Basic | beta |

---

##### Useful links for development Apache Modules:

- [Extending Apache](http://www.fmc-modeling.org/category/projects/apache/amp/3_3Extending_Apache.html)
- [Introduction to Buckets and Brigades](http://www.apachetutor.org/dev/brigades)
- [Writing Filters for Apache 2.0](http://www.onlamp.com/pub/a/apache/2001/08/23/apache_2.html)
- [Writing Apache 2.0 Output Filters](http://www.onlamp.com/pub/a/apache/2001/09/13/apache_2.html)
- [Writing Input Filters for Apache 2.0](http://www.onlamp.com/pub/a/apache/2001/09/20/apache_2.html)
- [Apache](http://ci.apache.org/projects/httpd/trunk/doxygen/modules.html)
- [APR 1.4](http://apr.apache.org/docs/apr/1.4/modules.html)
- [APR-Util 1.4](http://apr.apache.org/docs/apr-util/1.4/modules.htm)
- [API Changes in Apache HTTP Server 2.4 since 2.2](http://httpd.apache.org/docs/2.4/developer/new_api_2_4.html)

---
