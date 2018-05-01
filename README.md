# ASNDNS
Config repo for ASN
Contains build scripts for Bind server. 
Contains BIND config files and Zone files for ASN Authoritative Master DNS Server.

## Privacy/security note: 
Whilst we do not believe this presents a significant "infosec" danger, it is a potentially powerful way to see all the DNS info related to ASN. As ASN is basically an ISP, and all hosts listed here are likely to be easily found elsewhere, this should have limited use. 
The only vaguely "private" parts of this are likely to be things like Google verification codes and the like - put in a comment to remind people to add it, and manually edit this later if the organisation that "owns" that zone is worried about this sort of thing. Keep a single global note of all these in case you ever have to "push" the entire config in one go and wipe such info out. 
