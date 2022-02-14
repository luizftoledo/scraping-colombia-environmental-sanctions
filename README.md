# Scraping environmental sanctioned people in Colombia
 This scraper gets every environment sanction in Colombia from 2015 to 2022 using Python/Selenium.
 I have visited [this website](http://vital.minambiente.gov.co/SILPA_UT_PRE/RUIA/ConsultarSancion.aspx?Ubic=ext) and then chose a start ("fecha desde") and end ("fecha hasta") date to search for.
 The challeging part was to make the scrape visit the page, get the table and then move to the next page. There were hundreds of pages.
 The outcome CSV can be found [here](https://github.com/luizftoledo/scraping-colombia-environmental-sanctions/tree/main/outcome).
