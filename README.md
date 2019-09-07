# 07-Project-1

Our goal is to utilize the Spotify API to:

  - Analyze top tracks, albums, artists and genres to determine if their respective audio characteristics, defined by Spotify as things such as 'energy', 'danceability', 'length of song', etc, differ across different US states, countries and geographic regions of the world. 
  
  - Deterimine if characteristic differences are correlated with varying independent variables such as levels of crime, freedom,    languages, etc. across different different geographic regions.
  
  - Determine if the aggregate/mean audio characteristics of the Billboard Top 100 songs have shown meaningful changes :
        - across time, going back as far as possible
        - across R vs. D White House administrations
        - within war vs. non-war periods (i.e., Korean, Vietnam, Iraq)
        - vs. annual unemployment rates

  - Compare current Spotify 'popularity' ratings of songs across decades to determine if:
        - popularity of certain decades' music persists across time
  
  - Determine if the prevelance of certain genres as a % of Top 100 songs changes materially across time 
  
  ************ADD IDEAS WHERE APPROPRIATE************ 

  Progress: 9-6-19
    - Brandon was able to create a .csv file of the historical top 100 Billboard songs from 1955 to 2018.
        This provides both the time period and popularity facts that we were looking for.
        
    - We should determine if we still want to pursue the world event cause and effect on popular music or 
      if we want to pursue the decades style approach.  In either case, it will improve the content of the 
      presentation to make note of a few major themes of the eras highlighted to relate to the mood of the music.
    
    - Brandon was able to retrieve the playlist from the same source that gave the top 100 billboard data.
      If we can access these songs in spotify, we only need to pull object info about those songs now which
      should help to simplify what we use spotify for.  Just song characteristics for the songs chosen on the
      csv song list are needed.
    
    I think we can define our next project steps as follows: (let's discuss in class)
          1. Identify time eras or events.
          2. Identify the music that represents that era.
          3. Research and graph the characteristics of that music.
          4. Make some analysis and observations about the correlation to events and the change over time.
          5. Put it into a presentation and make it pretty.
          
   Additionally, I was unable to successfully get into spotify..  
          1. I should try again in class and we should verify that Chris can access as well.  
          2. We should push the working code and csv to git hub.  Once we get some basic data pulled from spotify, we should push a master file and create separate branches for the 3 of us to work on different graphs or eras..  (or work together and copy code for each era..  )
   We should push the working docs to git hub.
