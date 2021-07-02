# ABAP
Abap Development details

Some New Idea which I want to develop.

First One
# Use case
     SAP Hana Able to handle the Currency conversion inside the DB level, which increase the Performance of program.
# Problem
    Currently ( Assumption ) all the Hana Migration team, will change the code after move to Hana System, They change the code from the conversion on Application server level / on the Program level to DB via CDS view and Code push down ( CDS view / AMDP )
    
# Automate
    To change the Program line, which convert the quantity and Currency will done in Program level, which is same. The way the replace the logic also the same. 
    So we can Automate this process.
    
# Steps
   First identify the Place where the conversion is done use the SCAN key word
   find the corresponding variable used on select statement.
   convert the select statement as CDS view.
   Replace the Select statement table with CDS with converted quantity / currency Field
   Replace the ABAP lines of code for the conversion with new attribute.
    

