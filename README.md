# Uber_CaseStudy

This case study focuses on analysing the business problem that the cab company faces and suggest possible solutions. 


                                                                            
##              Understanding the data - Metadata  description               

Description     - Masked data set containing Uber cab request details
 
Source          - Assignment 
Format          - .csv (comma seperated values)
 
Number of rows  - 6745
 
Number of cols  - 6
 
Each row has    - Uber cab request detail
 
Sampling method - Data is for 5 days (Days 11 through 15 in the month of June for the year 2016) 

 
Column Details
 
Request.id       - Type: Number   | A unique identifier of the request 
                                              Missing : 0    | Uniques : 6745

Request.timestamp- Date timestamp | The date and time at which the customer made the trip request
                    Missing : 0    | Uniques : 5618
 
Drop.timestamp   - Date timestamp | The drop-off date and time, in case the trip was completed 
                      Missing : 3914 | Uniques : 2598
Pickup.point     - Character      | The point from which the request was made
                                        Missing : 0    | Uniques : 2

Driver.id        - Number         | The unique identifier of the driver
                                              Missing : 2650 | Uniques : 301 
Status           - Character      | The final status of the trip, that  can be either completed, cancelled by the driver or no cars available
                    Missing : 0    | Uniques : 3

                                                                          




Below steps were followed to understand and derive insights. 
All the steps folowed are available in the R file available in the repository. 

  Data Cleanup
  
  Deriving new variables
  
  GGplot to visualize
  
  Univariate and Segmented analysis

The detailed analysis on the demand supply gap, issues, possible causes and the recommended solution are all available in the PDF file in this repository







