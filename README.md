## Searchterm
Detect search keywords if referer coming from search engine

### Usage
```php
use Opendisk\SearchTerm\SearchTerm;

$term = SearchTerm::get();

/*
Example result:
(string) "kacang rebus"
*/

$isCameFromSE = SearchTerm::isCameFromSearchEngine();
/*
Example result:
(true)
*/
```

### License
MIT