# eprice-package
This package alows the user to get an e-commerce product's **title** and **price** as **tuple** according to the user's input **url**.

### List of e-commerce websites that can be requested through this package:

    *Amazon
    *Flipkart
    *Snapdeal
    *Alibaba
    *Reliance digital

### Importing and using the package:

``` python
from eprice_pkg import eprice

Title,Price=eprice.getAmazon(url)

Title,Price=eprice.getAlibaba(url)

Title,Price=eprice.getFlipkart(url)

Title,Price=eprice.getSnapdeal(url)

Title,Price=eprice.getReliancedigital(url)
```

#### NOTE: be aware of the region you request for because the functions retunrs the prices acording to the url the user searches for.
#### NOTE: be aware of the quantity while providing the link from alibaba.



