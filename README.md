#Stock Hawk

Added enhancements to one app in order to make it production ready. The work included ensuring errors were handled gracefully, building a widget for the home screen, adding support for screen readers, optimizations for localization, and data visualization via a library.

##Implementations 

- Each stock quote on the main screen is clickable and leads to a new screen which graphs the stock's value over time.
- Stock Hawk does not crash when a user searches for a non-existent stock.
- Stock Hawk Stocks can be displayed in a collection widget.
- Stock Hawk app has content descriptions for all buttons.
- Stock Hawk app supports layout mirroring using both the RTL attribute and the start/end tags.
- Strings are all included in the strings.xml file and untranslatable strings have a translatable tag marked to false.

##Installation

Simply download or fork this repository and import into Android Studio. No API key required.

##Screenshots

![Phone Main Layout](https://github.com/akshatgoel20/StockHawk/blob/master/Screenshot_2016-10-19-14-55-12.png)

![Phone Detail Layout](https://github.com/akshatgoel20/StockHawk/blob/master/Screenshot_2016-10-19-14-55-28.png)

![Widget Image](https://github.com/akshatgoel20/StockHawk/blob/master/Screenshot_2016-10-19-12-52-45.png)
