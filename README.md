# Fresh Resolvers
List of fresh DNS resolvers updated daily

```
$ wget https://raw.githubusercontent.com/kh4sh3i/Fresh-Resolvers/master/resolvers.txt
$ subfinder -d example.com | shuffledns -d example.com -r resolvers.txt
$ massdns -r resolvers.txt domains_to_resolve.txt
```

[DNS Validator](https://github.com/vortexau/dnsvalidator) is used to validate DNS resolvers from [public-dns.info](https://public-dns.info/nameservers.txt), which is pushed to this repository every day.

This list can be used with other tools that make use of resolves like [shuffledns](https://github.com/projectdiscovery/shuffledns), [massdns](https://github.com/blechschmidt/massdns), [zdns](https://github.com/zmap/zdns) etc



### Thanks
* [@vortexau](https://twitter.com/vortexau) and [@codingo_](https://twitter.com/codingo_) for creating dnsvalidator!
* GitHub for hosting this on GitHub Actions! 
