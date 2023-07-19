# SQL-Queries-


<h2>Description</h2>

The purpose of the first project was to investigate security issues. There have been some recent potential issues including log in attempts. (The data and the company in this project is fictional for the purpose of practicing and showcasing my skills in SQL) <br/>

The first thing I did was retrieve all of the data showing failed Log In attempts after 18:00 :  <br/>

<p align="center">
<img src="https://lh3.googleusercontent.com/pw/AIL4fc9yUAs2WiOe9aH6fU_BVW1N7xHEux-a6zVOHtVFhJFDSKlAlNzU27R-H6Nt8awBG6D5EFfD5S7lXWRbpuvW4_3vyjiL--FBJSVIzHCweQScT19aY1WXUmPLqRmcjsMwSWyJ1n8ak1f4U7eUbNOaH13t=w914-h468-s-no?authuser=0" height="80%" width="80%" alt="Failed Login After Hours"/>
<br />
  
I originally ordered it by login_time, however, this isn’t very helpful since the attempts were all on different days. 

We know that the incidents had to have taken place on or before May 9, 2022. So I altered the filter to view this. 

<p align="center"> 
<img src="https://lh3.googleusercontent.com/pw/AIL4fc_DAIOcurPe_jO_eFDw7zLrbJDhvAKJ4ZxdptgVNK9OtDMyHLOuk0Y4PwQK2eJ3d-8yAXPkf5LDH8Ph9P2ni6koWVQ4m6Tdl4QPQron9lwarl4QbGi36vntGS-oVKfI9XKUBnj6I_2bWv2EpypjEJu0=w809-h533-s-no?authuser=0" height="80%" width="80%" alt="May 9, 2022"/>
<br />


Now, we know that the attempts did not come from Mexico. I altered the filters to look for the entries not in Mexico. Some of the countries in this table were shortened so instead of searching the entirety of the country name, I used % in order to capture all of the data I was looking for. 

<p align="center"> 
<img src="https://lh3.googleusercontent.com/pw/AIL4fc_8PmfW4nZ20i1AgfdIDp-bRoK_EyqQAe4kIYO8ASs7BgBrZcaiLpqZK2HcsBIiaYIefHkEC9QhaypxBNTdWdB5RZ8WRblRQFERILXOthuC4P7NrB9Hjwza65hon21FzTUGUeF2KGOcCsEP8gxKuGkq=w813-h519-s-no?authuser=0" height="80%" width="80%" alt="Not in Mex"/> 
<br />
  

I then shifted to a different project, where the security team was gathering information regarding employees and machines in order to run updates according to the different department availability. I first looked up all of the employees in the Marketing Department 

<br />
<p align="center"> 
  <img src="https://lh3.googleusercontent.com/pw/AIL4fc9Xrkuwtw3T9BAU-6oMghuFsGFW1o9OCmhL1LWAAfVZE4iExitVsrZQuU_NJA4smuwn_tPWdqWnIKSZAHVcCLJUf2YQnsKYiK2MNxFXLYirVkbjld6hZbU5KgQ6CZs8AwyJjfBMyzlEjuEwCr5EVjGt=w917-h257-s-no?authuser=0" height="80%" width="80%" alt="Marketing Department"/><br />

Additionally, the security team wanted to run updates on the machines for the employees in the Finance and Sales departments. 
<br />


<p align="center"> 
<img src="https://lh3.googleusercontent.com/pw/AIL4fc9Raf4GB8coNfMfkpCsFKXdrPe3qZb35oa0qT_TIBtdOzTFAx-vbnwvczNq0qMf9IjYvZWSv2wL-4d6sG-5wpyeaPLIsbn9xKtFFsrjWmdj4GB9xh5Ctjp-RqFevd0Tvb8dnk1H2JjHAkxINOmlBJwG=w917-h523-s-no?authuser=0" height="80%" width="80%" alt="Sales or Finance"/><br />

The last request from the team is that I gather the information for all the employees except the employees in the IT department. 
<br />

<p align="center"> 
<img src="https://lh3.googleusercontent.com/pw/AIL4fc8w-3lKvUk8ec7GKQgAXAqD5Lcy2Ic7pE6oxosiHzzWcE4_VXIp74kVkuKVt2kDM0xWarzf-a3sURW330TQUy5XWiMORN2QCm4oc7YM0QHhm7N5OD_p5gPW0GTgiB-LQceHnykHd_m5RaTYDnw3yUeN=w730-h401-s-no?authuser=0" height="80%" width="80%" alt="only user"/>

<h2>Summary</h2>
I applied different commands and filters to query specific information that was relevant to the business goals. The purpose of querying the log_in_attempts table was to identify failed log in attempts and to gather information that was relevant to the search of the breach. The purpose of the query of the employees table was to gather information about employees, different departments, and office buildings to assist with the security teams goals of running updates. 
