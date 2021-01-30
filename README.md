# Python-for-DS-task2
All CSV files must have the following columns
- web_browser
        The web browser that has requested the service
- operating_sys
        operating system that intiated this request
- from_url

        The main URL the user came from

    **note**:

    If the retrived URL was in a long format `http://www.facebook.com/l/7AQEFzjSi/1.usa.gov/wfLQtf`

     make it appear in the file in a short format like this `www.facebook.com`
     
    
- to_url

       The same applied like `to_url`
   
- city

        The city from which the the request was sent
    
- longitude

        The longitude where the request was sent
- latitude

        The latitude where the request was sent

- time_zone
        
        The time zone that the city follow
        
- time_in

        Time when the request started
- time_out
        
        Time when the request is ended
        
        
**NOTE** :

Because that some instances of the file are incomplete, you may encouter some NaN values in your transforamtion. Make sure that the final dataframes have no NaNs at all.
