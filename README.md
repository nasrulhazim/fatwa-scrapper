## Fatwa Scrapper

Fatwa scrapped from [here](http://e-smaf.islam.gov.my/e-smaf/index.php/main/mainv1/fatwa/) and store in JSON format.

At the moment the scrapper only only get the Fatwa ID and the generate the URL to Fatwa details.

Latest scrapped on Mar 9, 2019 - see `storage/data/20190309075302.json`.

## Usage

Clone this repository, navigate to the repository and run the following command:

```
$ ./fatwa
```

## Todo

Scrap the following details to be store in JSON format as well:

- [x] Id 
- [x] URL to Fatwa Details
- [ ] Tajuk
- [ ] Kategori
- [ ] Tahun
- [ ] Status Pewartaan
- [ ] Negeri
- [ ] Keputusan 

> Might consider to structure the data using OpenAPI Standard.

## More Information

Read the documentation of the [BrowserKit](https://symfony.com/components/BrowserKit) and [DomCrawler](https://symfony.com/doc/current/components/dom_crawler.html) Symfony Components for more information about what you can do with Goutte.

## Technical Information

The scrapper use Goutte.

Goutte is a thin wrapper around the following fine PHP libraries:

Symfony Components: [BrowserKit](https://symfony.com/components/BrowserKit), CssSelector and [DomCrawler](https://symfony.com/doc/current/components/dom_crawler.html);
Guzzle HTTP Component.

## License

Fatwa Scrapper is licensed under the MIT license.
