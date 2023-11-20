---
title: "Assignment 3"
excerpt_separator: "<!--more-->"
categories:
  - Blog
tags:
  - assignment
  - afra
  - idh
---

Assignment 3 With Afra 

# Assignment 3 Spatial Data


## Step 1 

![alt text](coverpage.jpg)
 
 Our decision to rely on [Source #8](https://archive.org/details/Directory_201704/page/n545/mode/2up), specifically the UAE Exports & Industry Directory, was driven by its comprehensive coverage of the UAE's exports across various sectors. This directory serves as a crucial industry guide for the years 2017-2018, prepared under the guidance of the government of Dubai with data compiled from diverse industries, including the Food Industry, Jewelry Industry, Insurance Companies operating in the UAE, and our primary focus, the Banking Sector.

Our exploration of the directory centered on the banking sector, with a specific focus on foreign banks in Dubai, amidst the various industries documented in 2017. Notably, Dubai stands out for its cultural diversity, hosting more than 200 nationalities, according to the UAE's Ministry of Foreign Affairs. As of 2010, the population demographics reveal 947,997 Emiratis and a substantial expatriate population of 7,316,073. The dominance of expatriates, exceeding the number of Emiratis by the millions, underscores the imperative for foreign banks to establish accessibility throughout the city.

Understanding the unique demographics of Dubai is pivotal for businesses, especially those in the banking sector. The city's cosmopolitan nature demands financial institutions strategically position themselves to cater to the needs of both the local Emirati population and the diverse expatriate community. This aligns with Dubai's status as a global business hub, underscoring the importance of creating a banking infrastructure that accommodates the dynamic and multicultural fabric of the city.


## Step 2

![alt text](datalist.jpg)

For Step 2, of our spatial modeling assignment, our initial focus was on structuring the data for effective geolocation. We opted to categorize the data into four key columns using ChatGPT: Bank Name, Address, Phone, and Website. While the Phone and Website columns were not primary factors for geolocation, we deemed them as additional, aesthetically pleasing information.

[CSV](https://docs.google.com/spreadsheets/d/1OLWrIS-Jv8SFAemDNLiFyYxwIWU3PTp7FC6FAbsOHJ4/edit?usp=sharing)

We didn’t have to use ChatGPT because the data was generally organized, however we just did it to test it out, and we thought it would ease the process without having to endure the pain of deleting and spacing out unwanted information.


## Step 3+4

![alt text](w.jpg)

![alt text](e.jpg)

![alt text](q.jpg)

We employed the "geocode by awesome table" extension. However, this approach encountered challenges. The primary issue arose from the fact that these foreign banks also operated as local banks in other parts of the world. As a result, when uploading the initial CSV file onto Kepler.gl, the mapping erroneously included locations in countries like Iran, Turkey, and Kuwait.

To address this issue, we introduced two new columns: City and Address_Plus. Address_Plus was created through the concatenation of the Bank Name, Address, and City columns. Despite this modification, the geolocation process faced similar challenges, with inaccurate mappings persisting when uploading the CSV file onto Kepler.gl.

Recognizing the limitations of the initial dataset, we delved deeper into the intricacies of street naming conventions in the UAE. Given recent changes to street names and the prevalence of shared street names across Arab countries, we identified discrepancies in the dataset. Additionally, some streets were named in honor of other Arab countries and notable figures, contributing to the inaccuracies.

In response, we conducted a thorough verification process by cross-referencing the data on Google Maps, obtaining the most up-to-date addresses for the banks. Some banks had undergone name changes, and certain streets were found to be misspelled. Armed with this corrected information, we repeated the geolocation process, resulting in a successful outcome. All data points were accurately pinned within Dubai, providing us with a refined and reliable spatial dataset for our modeling assignment.

