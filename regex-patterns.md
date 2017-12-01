# Regular Expression Patterns
A handful of Regular Expression patterns that I wrote / found from the internet that I think it's worth sharing

## Media File Urls Extraction
Extract multille media file urls from a string.

### Sample Use Case
Extract links from emails that contain urls of images or videos so you can download them

### Pattern
```
/(?<fullUrl>(https?:\/\/([a-z0-9\-]+\.)+[a-z0-9]+\/)([a-z0-9\-%_]+\/)*(?<fileName>[a-z0-9\-%_]+\.(jpe?g|gif|png|flv|mp[2|4|a|e|g|eg|v2]|mov|qt|3g2|3gpp2|3gp|wmv|avi)))/igU
```