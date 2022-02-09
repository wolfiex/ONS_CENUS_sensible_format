# ONS_CENUS_sensible_format
A directory to extract ons data in a *god forbid* intuitive format. 

### Process
- get bulk page url 
- create headless chrome browser
- navigate to page
- strip source code
- select table
- select items from table 

For each item in parallel:
- download in memory
- unzip in RAM
- read each zipped file
- merge individual data tables
- use description table to assign headers
- save 
