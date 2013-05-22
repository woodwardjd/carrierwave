* rails engine / something-or-other to set up a route to initiate a
  persistent cache pull in the case of a missing file
* help protect against DOS by using a fast "is this file in the
  persisted cache" answering mechanism like redis 
* tests!
