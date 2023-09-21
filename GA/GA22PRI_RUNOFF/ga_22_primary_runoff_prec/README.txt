Georgia 2022 Primary Election Precinct-Level Results

## RDH Date Retrieval
09/13/23

## Sources
The RDH retrieved 2022 precinct election precinct-level results from the Georgia Secretary of State [website] (https://results.enr.clarityelections.com/GA/114891/web.285569/#/reporting). The RDH navigated to each county's election results page and clicked 'Detail XML', to get the results at the precinct level

## Notes on Field Names (adapted from VEST):
Columns reporting votes generally follow the pattern: 
One example is:
G16PREDCLI
The first character is G for a general election, P for a primary, S for a special, and R for a runoff.
Characters 2 and 3 are the year of the election.*
Characters 4-6 represent the office type (see list below).
Character 7 represents the party of the candidate.
Characters 8-10 are the first three letters of the candidate's last name.

*To fit within the GIS 10 character limit for field names, the naming convention is slightly different for the State Legislature, Public Service Commissioners and US House of Representatives. All fields are listed below with definitions.

Office Codes Used: 
AGR - Commissioner of Agriculture
ATG - Attorney General
COA - State Court of Appeals
GOV - Governor
INS - Commissioner Of Insurance
LAB - Commissioner Of Labor
LTG - Lieutenant Governor
PSC# - Public Service Commissioner
SOS - Secretary Of State
SUP - State School Superintendent
USS - U.S. Senate
CON## - U.S. Congress
SL###  - State Legislative Lower
SSC - State Supreme Court
SU##  - State Legislative Upper


## Fields:
Field Name Description
UNIQUE_ID  Unique ID for each precinct                                
COUNTYFP   County FIP identifier                                      
county     County Name                                                
precinct   Precinct Name
R22LTGDBAI Bailey, Charlie - Lieutenant Governor - Dem                
R22LTGDHAL Hall, Kwanza - Lieutenant Governor - Dem                   
R22SOSDNGU Nguyen, Bee - Secretary of State - Dem                     
R22SOSDDAW Dawkins-Haigler, Dee - Secretary of State - Dem            
R22INSDROB Robinson, Janice Laws - Commissioner of Insurance - Dem    
R22INSDBAK Baker, Raphael - Commissioner of Insurance - Dem           
R22LABDBOD Boddie, William Will Jr - Commissioner of Labor - Dem      
R22LABDHOR Horn, Nicole - Commissioner of Labor - Dem                 
RCON01DHER Herring, Wade - US House - District 1 - Dem                
RCON01DGRI Griggs, Joyce Marie - US House - District 1 - Dem          
RCON02RWES West, Chris - US House - District 2 - Rep                  
RCON02RHUN Hunt, Jeremy - US House - District 2 - Rep                 
RCON06RMCC McCormick, Rich - US House - District 6 - Rep              
RCON06REVA Evans, Jake - US House - District 6 - Rep                  
RCON07RGON Gonsalves, Mark - US House - District 7 - Rep              
RCON07RCOR Corbin, Michael - US House - District 7 - Rep              
RCON10DJOH Johnson-Green, Tabitha - US House - District 10 - Dem      
RCON10DFOR Fore, Jessica Allison - US House - District 10 - Dem       
RCON10RCOL Collins, Mike - US House - District 10 - Rep               
RCON10RJON Jones, Vernon - US House - District 10 - Rep               
RSU03RHOD  Hodges, Mike - State Senate - District 3 - Rep             
RSU03RJON  Jones, Jeff - State Senate - District 3 - Rep              
RSL024RBAR Barrett, Carter - State House - District 24 - Rep          
RSL024RGIL Gilligan, Sheri Smallwood - State House - District 24 - Rep
RSL028RCOX Cox, Brent - State House - District 28 - Rep               
RSL028RTRE Tressler, Julie - State House - District 28 - Rep          
RSL030RMCC McCollum, Derrick - State House - District 30 - Rep        
RSL030RPIM Pimentel, Whitney - State House - District 30 - Rep        
RSL039DCUM Cummings, Terry - State House - District 39 - Dem          
RSL039DDEL Delancy, Monica Evette - State House - District 39 - Dem   
RSL050RRED Reddy, Narender - State House - District 50 - Rep          
RSL050RKRA Kramer, Betsy - State House - District 50 - Rep            
RSL061DBRU Bruce, Roger - State House - District 61 - Dem             
RSL061DKEM Kemp, Rashaun - State House - District 61 - Dem            
RSL086DBAR Barnes, Imani - State House - District 86 - Dem            
RSL086DADA Adams, Jacqueline - State House - District 86 - Dem        
RSL090DDRA Draper, Saira - State House - District 90 - Dem            
RSL090DSCH Schreiner, Michelle - State House - District 90 - Dem      
RSL117RDAN Daniel, Lauren - State House - District 117 - Rep          
RSL117RKAH Kahaian, Noelle - State House - District 117 - Rep         
RSL179RTOW Townsend, Rick - State House - District 179 - Rep          
RSL179RDUN Duncan, Bob - State House - District 179 - Rep                                                           

## Processing Steps
Visit the RDH GitHub and the processing script for this code [here](https://github.com/nonpartisan-redistricting-datahub/pber_collection/tree/main/GA/2022)

Please direct questions related to processing this dataset to info@redistrictingdatahub.org.
