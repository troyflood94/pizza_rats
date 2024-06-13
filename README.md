# pizza_rats
Analyzing correlation between Restaurant rating and Rat sightings in NYC

1. How many A, B, C restaurants were there from September 2010-September 2017?
2. How many rat sitings were there from September 2010-September 2017?
3a. Do certain boros have higher restaurant ratings? (Bar Graph)
3b. Do certain boros have more rat sightings? (Bar Graph)
4. Is there a relationship between rats and restaurant ratings?
4a. Is there a correlation between rat sighting and restaurant rating? (Scatterplot)
4b. Is there an association between restaurant type and rating? (Line Graph)
4c. Do places with more rats have fewer restaurants? (Scatterplot)
4d. Do restaurants closed by DOHMH tend to be in "high rat areas"? (Bar Graph)


columns to keep (+ date for both) (we will need to keep clean_rats_df['Location Type'] as well, for filtering the sightings to just restaurants)
1. clean_grade_df['GRADE']
2. clean_rat_df['Complaint Type']
3a. clean_grade_df['GRADE'],clean_grade_df['BORO']
3b.clean_rat_df['Complaint type'],clean_rat_df['BORO']
4. clean_rat_df['complaint Type'],clean_grade_df['GRADE']
4a. clean_rat_df['complaint Type'],clean_grade_df['GRADE']
4b. clean_grade_df['GRADE], clean_grade_df['cuisine_description']
4c. clean_rat_df['boro'], clean_grade_df['boro']
4d. 

I was thinking about our questions given the data we have, how does this look?

1a.How many A, B, C graded restaurants were there in New York City from September 2010-September 2017?
1b. Is there an association between restaurant type and rating?

2.How many rat sightings were there in New York City from September 2010-September 2017?
Do certain Boroughs have higher restaurant ratings?

3a. Do certain Zip Codes have higher restaurant ratings?
Do certain Boroughs have more rat sightings?

4a. Do certain Zip Codes have more rat sightsings?
Is there a relationship between rats and restaurant ratings?

5a. Do zip codes with more rats have fewer A restaurants?
5b. Do "high rat" zip codes have more restaurants closed by DOHMH when compared to "low rat" zip codes?

1a.clean_grade_df['GRADE']
1b. clean_grade_df['GRADE], clean_grade_df['cuisine_description']
2.clean_rat_df['Complaint Type']