<h1>Preparing and Cleaning Data in SQL</h1>



<h2>Description</h2>
Using SQL to clean automobile data. Data obtained through Google Data Analytics Certificate program.
<br />


<h2>SQL FUNCTIONS AND COMMANDS USED</h2>

- <b>DISTINCT</b> 
- <b>MIN</b>
- <b>MAX</b>
- <b>AS</b>
- <b>WHERE</b>
- <b>SET</b>
- <b>AND</b>
- <b>UPDATE</b>

<h2>Environment Used </h2>

- <b>BIG QUERY</b> 

<h2>Walk-through:</h2>

<p align="center">
1. Confirm column "fuel_type" doesn't have any unexpected values. Expected values = 2: Gas and Diesel.  <br/>
<img src="https://i.imgur.com/Oa5wzBu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
2. Inspect the length column. The "length" column contains the lengths of the cars. Lengths should range 141.1-208.1.  <br/>
<img src="https://i.imgur.com/ImsUqrM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
3. Check Data for Null values. Discovered null value in column "num_of_doors". <br/>
<img src="https://i.imgur.com/OltOqpI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
4. Update Missing Data. We know that all Mazda diesel sedans sold had 4 doors. <br/>
<img src="https://i.imgur.com/YbQ0lSE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />




