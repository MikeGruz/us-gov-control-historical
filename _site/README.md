# us-gov-control-historical

Dataset that tracks control of the United States House of Representatives, Senate, and Executive Branch. 

Variables should be fairly self-explanatory, but are as follows:  
*congress:* Numeric identifier of Congressional session  
*year.start:* Start year of Congressional session  
*year.end:* End year of Congressional session 
 
*senate.total:* Total number of Senate seats in that session  
*senate.dems:* Total number of Democrats in Senate  
*senate.dem.perc:* Percentage of Senators from Democratic Party  
*senate.reps:* Total number of Republicans in Senate  
*senate.rep.perc:* Percentage of Senators from Republican Party  
*senate.others:* Number of independents in Senate  
*senate.vacancies:* Number of vacancies in Senate (in total)  
*senate.dem.control:* Democratic Party controlled Senate  
*senate.rep.control:* Republican Party controlled Senate  

*house.total:* Total number of House seats in that session  
*house.dems:* Total number of Democrats in House  
*house.dem.perc:* Percentage of House Reps from Democratic Party  
*house.reps:* Total number of Republicans in House  
*house.rep.perc:* Percentage of House Reps from Republican Party  
*house.others:* Number of independents in House  
*house.vacancies:* Number of vacancies in House (in total)  
*house.dem.control:* Democratic Party controlled House  
*house.rep.control:* Republican Party controlled House  

*congress.dem.control:* Democratic Party controlled both chambers  
*congress.rep.control:* Republican Party controlled both chambers  
*congress.div.control:* Chambers divided between Democrats/Republicans

*pres.dem:* Dummy variable indicating Democratic president  
*pres.rep:* Dummy variable indicating Republican president  
*pres:* Name of president 

**A few notes about Senate control**

In several Congressional sessions Democrats gained an effective majority in the U.S. Senate due to independents caucausing with the Democratic Party. These sessions have been noted as being under Democratic control as a result:  
* 107th Senate (only under Republican control from January-May 2001)  
* 110th Senate 

The 111th Senate is a tough one to code for an entire session, as it varied in [Democratic control of 56-58 seats at multiple time points](https://en.wikipedia.org/wiki/111th_United_States_Congress). However, the predominant breakdown was 57 Democrats to 41 Republicans, with two independents caucausing with the Democrats.

**Presidents Leaving Early**

In cases where presidents left office due to death, resignation, or impeachment, the president who occupied the Oval Office for the majority of that period was coded for. With the exception of Republican Abraham Lincoln's assassination (and Democratic/National Union Party Andrew Johnson's ascendance), no shifts in party control occurred due to early departure from that office.
