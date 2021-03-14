## Hacking with Google

#### Commands (or "dorks") for the world's most popular search engine

* __cache__ - this command will show you the cached version of any website.
`cache: securitytrails.com`

* __allintext__ - searches for specific text contained on any web page.
`allintext: hacking tools`

* __allintitle__ - exactly the same as allintext, but will show pages that contain titles with X characters.
`allintitle:"Security Companies"`

* __allinurl__ - it can be used to fetch results whose URL contains all the specified characters.
`allinurl client area`

* __filetype__ - used to search for any kind of file extensions, for example, if you want to search for jpg files you can use:
`filetype: jpg`

* __inurl__ - this is exactly the same as allinurl, but it is only useful for one single keyword.
`inurl: admin`

* __intitle__ - used to search for various keywords inside the title, for example,
`intitle:security tools` will search for titles beginning with “security” but “tools” can be somewhere else in the page.

* __inanchor__ - this is useful when you need to search for an exact anchor text used on any links.
`inanchor:"cyber security"`

* __intext__ - useful to locate pages that contain certain characters or strings inside their text.
`intext:"safe internet"`

* __link__ - will show the list of web pages that have links to the specified URL.
`link: microsoft.com`

* __site__ - will show you the full list of all indexed URLs for the specified domain and subdomain.
`site:securitytrails.com`

* __*__ - wildcard used to search pages that contain “anything” before your word.
For example, `how to * a website`, will return “how to…” design/create/hack, etc… “a website”.

* __|__ - this is a logical operator, for example, `"security" "tips"` will show all the sites which contain “security” or “tips,” or both words.

* __+__ - used to concatenate words, useful to detect pages that use more than one specific key.
`security + trails`

* __–__ - minus operator is used to avoiding showing results that contain certain words, for example, `security -trails` will show pages that use “security” in their text, but not those that have the word “trails.”
