### URL

A URL are made of different parts
* protocol: `http`, `https` => ssl certificates
* host (comprises subdomain): `mydomain.com` => domain setup, subdomain configuration
* path: `/my/path` => route setup for static apps
* query: `?p=1&q=2`

`uri` should not be used, it is officially deprecated. 
 > Standardize on the term URL. URI and IRI are just confusing. In practice a single algorithm is used for both so keeping them distinct is not helping anyone. URL also easily wins the search result popularity contest.

[reference](https://url.spec.whatwg.org/#goals)

see
* https://en.wikipedia.org/wiki/URL#Syntax
* https://nodejs.org/api/url.html#url_url_strings_and_url_objects
* https://www.mattcutts.com/blog/seo-glossary-url-definitions/
* https://url.spec.whatwg.org/#url-apis-elsewhere
* https://en.wikipedia.org/wiki/Uniform_Resource_Identifier
