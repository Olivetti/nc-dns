# nc-dns v1.0
**nc-dns** is a management tool for [netcup's dns api](https://netcup-wiki.de/wiki/CCP_API)

based on [linxside's ncdapi](https://github.com/linxside/ncdapi)

### Dependencies
- [curl](https://github.com/curl/curl)
- [jq  ](https://github.com/stedolan/jq)

### Recommended
- [pass](https://passwordstore.org)

### Installation
1. [Download & unpack](https://github.com/Olivetti/nc-dns/releases/latest/download/nc-dns.tar.gz)
2. Set executable   `chmod +x nc-dns`
3. Create sidfile   `echo "0" > ~/.nc-dns.sid`
4. Change file mode `chmod 600 ~/.nc-dns.sid`
5. Edit credentials `nano env`

### Usage
- ./nc-dns -h

## Contributing
Issues can be made in [**GitHub** project](https://github.com/Olivetti/nc-dns)

## Contact
[Mastodon](https://mastodon.social/@Olivetti)
