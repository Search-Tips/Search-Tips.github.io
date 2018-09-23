# Google

Search on website for words

`google site:microsoft.com`

Show sites that talk about a specific site (example: github.com)

`"github.com" -site:github.com`

Search for word but skip specific TLD (top level domain)

`github -site:.com`

Search for file type (like PDF) with specific word (like "microsoft")

`filetype:pdf microsoft`

Search for file type (like PDF) under specific domain (like "microsoft.com")

`filetype:pdf site:microsoft.com`

Search for file type (like PDF) under specific domain (like "microsoft.com") and skip specific subdomain (like "nds1.webapps.microsoft.com")

`filetype:pdf site:microsoft.com -site:nds1.webapps.microsoft.com`

Search for sites with the same domain name at the end. The results are only displayed with a "-" minus sign between them. 
Warning: Many of these results may be potential phishing sites.

`site:*github.com -site:github.com`

Get map from search bar

`map:amsterdam`
