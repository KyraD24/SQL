# SQL

# Finding only the Capital City of a country
<img width="1078" height="519" alt="Image" src="https://github.com/user-attachments/assets/c916b89b-6f7e-47c3-81bb-92bffe01a070" />

# Finding all Countries in one Continent
<img width="1085" height="518" alt="Image" src="https://github.com/user-attachments/assets/643b0563-3c48-42b0-8082-5293240401a0" />

# Average city population
<img width="1065" height="414" alt="Image" src="https://github.com/user-attachments/assets/501d8636-96f9-413e-888f-4963d8c60457" />

## Query I used.

SELECT 
 	country.Name,
     CountryCode, 
 	AVG(city.Population) AS "Average City Population"

 FROM city

 JOIN country ON country.Code = city.CountryCode

 GROUP BY CountryCode;

 # Found city names beggining with 'Be'
<img width="1071" height="504" alt="Image" src="https://github.com/user-attachments/assets/339c39fc-a9af-4dbd-938b-d95f1565140e" />


# Amount of times the city was mentioned.
<img width="1073" height="517" alt="Image" src="https://github.com/user-attachments/assets/d259b58b-3626-4420-b3e3-e52d616253db" />
