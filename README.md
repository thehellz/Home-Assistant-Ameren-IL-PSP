
Home assistant configuration that uses multiscrape to pull current day and next day data from Ameren IL psp webpage. Places the scraped data into template sensors for hourly data. 


To use this add the multiscrape integration using [HACS](https://github.com/danieldotnl/ha-multiscrape). Then create a new file called multiscrape.yaml, copy/paste the contents into your newly created file. Add the !include multiscrape.yaml line into your configuration.yaml file. Do this for templates.yaml as well. 
