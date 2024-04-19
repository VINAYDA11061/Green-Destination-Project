
# Green Destination HR Dashboard

### Objective

Green Destination is a well known travel agency.The HR Director has recently noticed an increase in employees leaving(attrition). She would figure out any trends or patterns.She has surveyed the staff of Green Destinations and provided the data. 

She would like to know the attrition rate (% of people who left the company).

She would also know if factors like age, years at the company and income play a part in determining if people will leave or not.

### HR Dashboard

<div align="left">
</div>

![Green Destination HR dashboard](https://github.com/VINAYDA11061/Green-Destination-Project/assets/125648329/43d70b58-e6b1-4ec5-bee1-721f0933fb36)


# Tableau Dashboard link : 

https://public.tableau.com/app/profile/vinay.kumar.m/viz/GreenDestinationHRDashboard/Dashboard1?publish=yes 



### KPI's :
### Calculated Columns:
Active Employee = SUM([Employee Count])-SUM([Attrition  count])
Attrition Rate % = SUM([Attrition  count]) / TOTAL(SUM([Employee Count]))
Attrition Count =  IF [Attrition]="Yes" THEN 1 ELSE 0 END
