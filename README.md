# bmkg-api
A simple RESTful API for retrieving BMKG open data. See: https://data.bmkg.go.id/#data

``NOTE: ``  
> Only the Earthquakes data that is available at the moment. I will add the Weather Forecast data later.

### Setup   
  1. Run the `scraper.py` in cron jobs or in any scheduling system you know of.  
  2. Deploy the Flask App anywhere of your choice. If you are new to Flask App deployment, google is your best friend.
  
### API endpoint   
  * Gempa terbaru   
        `http://<your_domain>/api/bmkg/gempa/terbaru`
    
  * Gempa dirasakan   
        `http://<your_domain>/api/bmkg/gempa/dirasakan`
    
  * Gempa di atas 5 SR   
        `http://<your_domain>/api/bmkg/gempa/limasr`
