# bashScripts
Small helper bash scripts

## xenc
xenc uses OpenSSL to Encrypt/Decrypt files

Usage: `xenc -f FileToEncrypt.txt` OR `xenc -f FileToDecrypt.txt.xenc -d` 

## dnsall
dnsall uses dig to get all DNS records of a domain name

Usage 1: `dnsall <Domain_name>`
This will show the dns records of the following types: `A AAAA CNAME MX NS TXT PTR SOA SRV`

Usage 2: `dnsall <Domain_name> full`
This will show the dns records of the following types: `A AAAA CNAME MX NS TXT PTR SOA SRV AFSDB APL CAA CDNSKEY CDS CERT CSYNC DCHID DHCID DLV DNAME DNSKEY DS EUI48 EUI64 HINFO HIP HTTPS IPSECKEY KEY KX LOC NAPTR NSEC NSEC3 NSEC3PARAM OPENPGPKEY RP RRSIG SIG SMIMEA SSHFP SVCB TA TKEY TLSA TSIG URI WALLET ZONEMD MD MF MAILA MB MG MR MINFO MAILB WKS NB NBSTAT NULL A6 NXT X25 ISDN RT NSAP NSAP-PTR PX EID NIMLOC ATMA SINK GPOS UINFO UID GID UNSPEC SPF NINFO RKEY TALINK NID L32 L64 LP DOA`

