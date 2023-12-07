  
## DATA DOCUMENTATION  


### Original Data Sources  

*Seattle Pet Licenses Dataset*: https://data.seattle.gov/Community/Seattle-Pet-Licenses/jguv-t9rb  
- Original variables: Zip code, License issue dates, license numbers, names, primary breed, secondary breed  
Data origination: The City of Seattle, Department of Finance and Administrative Services  

*New York City Pet Licenses Dataset*: https://data.cityofnewyork.us/Health/NYC-Dog-Licensing-Dataset/nu7n-tubp  
- Original variables: Name, gender, birth year, breed, zip code, license issue date, license expired date  
Data origination: New York City, Department of Mental Health and Hygiene  

  
### NEW DATASET VARIABLES:

- Name (chr): Pet name  
- OverallRank (int): Rank of pet name, considering both Seattle and NYC  
- Seattle (int): Ranking of the name in Seattle  
- NYC (int): Ranking of the name in NYC  
- UniqueToSeattle (logical): Name is significantly more popular** in Seattle  
- UniqueToNYC (NYC): Name is significantly more popular** in NYC  
  
** "Significantly more popular in one city" means 70% of more counts of a particular name came from one city  
  
Number of Rows: 16,979  
Number of Columns: 6  
Number of missing/invalid values: NONE  
