<h4>Meet App<h4>The purpose of the Meet App will be to help users find events in different locations. The app will run on React platform using TDD.<br> 
  <br>FEATURE 2: SHOW/HIDE AN EVENT'S DETAILS –</br>
	<h6>AS A USER I SHOULD BE ABLE TO CLICK ON AN EVENT TO EXPAND IT SO THAT I CAN SEE THE DETAILS</h6>
  Scenario 1: An event element is collapsed by default
	<ul>
    <li>Given the user has not started a search</li>
    <li>When the user has not clicked on anything yet</li>
	  <li>Then the event details are collapsed or hidden</li>
  </ul>  
    Scenario 2: User can expand an event to see its details
   <ul>
    <li>Given the user has begun a search for a city</li>
    <li>When the user clicks on an event element</li>
    <li>Then the event details are shown</li>
  </ul>
    Scenario 3: User can collapse an event to hide its details
   <ul>
    <li>Given the user is no longer searching or not looking for details</li>
    <li>When the user clicks again on the details</li>
    <li>Then the event details collapse once again</li>
  </ul>
  <h4>FEATURE 3: SPECIFY NUMBER OF EVENTS -</h4>
  <h6>AS A USER I SHOULD BE ABLE TO SELECT HOW MANY EVENTS I WANT TO SEE SO THAT I CAN SEE 1 OR MORE EVENTS IF I CHOOSE</h6>
Scenario 1: When user hasn’t specified a number, 32 is the default number.
  <ul>
    <li>Given the user has not specified any number of events</li>
    <li>When the user begins the search</li>
    <li>Then 32 events are displayed by default</li>
  </ul>  
Scenario 2: User can change the number of events they want to see
  <ul>
    <li>Given the user has specified the number of events</li>
    <li>When the user specifies the number of events they want to see</li>
    <li>Then the user finally chooses the number of events</li>
  </ul>  
  <h4>FEATURE 4: USE THE APP WHEN OFFLINE</h4>
    <h6>AS A USER I SHOULD BE ABLE TO USE THE APP WHEN I’M OFFLINE OR THERE’S NO INTERNET SO THAT I CAN CONTINUE TO SEE EVENTS IF I CHOOSE</h6>
Scenario 1: Show cached data when there’s no internet connection
  <ul>
    <li>Given the user does not have Internet connectivity</li>
    <li>When the user needs to see events while offline</li>
    <li>Then the user will be able to see cached events</li>
  </ul>  
Scenario 2: Show error when user changes the settings (city, time range)
  <ul>
    <li>Given the user tries to make changes while offline</li>
    <li>When the user tries to change search settings information</li>
    <li>Then the user will get an error message that they’re not connected to Internet</li>
  </ul>  
  <h4>FEATURE 5: DATA VISUALIZATION</h4>
     <h6>AS A USER I SHOULD BE ABLE TO SEE A CHART WITH UPCOMING EVENTS (DATE/TIME) IN EACH CITY SO THAT I CAN MAKE A PROPER SELECTION FROM A CHART</h6> 
Scenario 1: Show a chart with the number of upcoming events in each city
  <ul>
    <li>Given the user wanted to see upcoming events in a city</li>
    <li>When the user views the chart of current or upcoming events</li>
    <li>Then the user will get a proper display of events</li>
  <ul>  
