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

Assignment 3 With Amal 

# Assignment 3 Spatial Data


## Step 1 

<img src="/assets/images/coverpage.jpg" style="zoom:100%;" />

 
Our choice to lean on Source #8, particularly the UAE Exports & Industry Directory, wasn't just a cold, calculated decision—it was driven by a deep curiosity about the heartbeat of Dubai's economic life. This directory, a labor of love guided by the government of Dubai for the years 2017-2018, stitches together the diverse stories of industries like a patchwork quilt. From the Food Industry to the glimmering Jewelry Sector, from the intricate web of Insurance Companies to our main squeeze, the Banking Sector, it's a tapestry that tells the tale of Dubai's economic dance.

Our journey through the directory was like wandering through a bustling marketplace, with each industry a vibrant stall offering its unique wares. The Banking Sector, our focus, emerged as a lively square in this marketplace, buzzing with activity. We zoomed in on the foreign banks in Dubai, those cultural bridges in a city that wears diversity like a badge of honor. Dubai, with its mosaic of more than 200 nationalities, is a place where numbers don't just tell a story—they sing it out loud.

Peeling back the layers, we discovered that the directory isn't just a list of names and figures. It's a treasure map, guiding us through the diverse streets of Dubai's financial landscape. Foreign banks aren't just entities; they're storytellers, each with a unique narrative etched in the market share they claim, the services they offer, and the communities they serve.

In a city where Emiratis share space with millions of expatriates, foreign banks aren't just service providers; they're architects of accessibility. They build bridges in a city where the population of expatriates dwarfs that of Emiratis. This isn't just about financial transactions; it's about weaving a banking infrastructure that understands the pulse of the city—a rhythm that harmonizes with both the local Emirati beat and the eclectic expatriate melody.

Dubai, with its cosmopolitan flair, demands a banking sector that dances to the rhythm of its people. The directory, like a backstage pass, gave us insights into this grand performance. It's not just about numbers; it's about understanding the soul of the city. The global business hub status of Dubai isn't just a tagline; it's a responsibility to create a banking landscape that respects and reflects the diverse tapestry of the city.

As we flipped through the pages of the UAE Exports & Industry Directory, it was more than just data—it was a journey through the streets, markets, and neighborhoods of Dubai's economic story. The foreign banks weren't just entries in a table; they were characters in a plot, contributing to the international trade narrative, supporting the city's global aspirations.

Regulations, often seen as the fine print, became the rules of engagement in this narrative. The directory, our guidebook, helped us navigate the regulatory landscape, making sense of the rules that shape the storyline of the banking sector. It wasn't just about compliance; it was about understanding the rules of the game in this bustling marketplace.

Beyond the Banking Sector spotlight, the directory opened windows into other industries. The Food Industry, the Jewelry Sector, and the Insurance Companies—they weren't just chapters; they were side stories, enriching our understanding of the economic novel that is Dubai.

In embracing the UAE Exports & Industry Directory, we didn't just choose a source; we embarked on a journey. It's not just a reference; it's a companion, guiding us through the human tapestry that is Dubai's economic landscape. Our reliance on this source isn't just a methodological choice; it's a commitment to telling a richer, more human story of Dubai's economic heartbeat.

## Step 2

<img src="/assets/images/datalist.jpg" style="zoom:100%;" />


For Step 2, of our spatial modeling assignment, our initial focus was on structuring the data for effective geolocation. We opted to categorize the data into four key columns using ChatGPT: Bank Name, Address, Phone, and Website. While the Phone and Website columns were not primary factors for geolocation, we deemed them as additional, aesthetically pleasing information.

[CSV](https://docs.google.com/spreadsheets/d/1OLWrIS-Jv8SFAemDNLiFyYxwIWU3PTp7FC6FAbsOHJ4/edit?usp=sharing)

We didn’t have to use ChatGPT because the data was generally organized, however we just did it to test it out, and we thought it would ease the process without having to endure the pain of deleting and spacing out unwanted information.


## Step 3+4

<img src="/assets/images/w.jpg" style="zoom:100%;" />


<img src="/assets/images/e.jpg" style="zoom:100%;" />


<img src="/assets/images/q.jpg" style="zoom:100%;" />


Our decision to employ the "geocode by awesome table" extension for the geocoding of foreign banks in Dubai encountered notable challenges during the initial stages of the process. The primary issue stemmed from the dual role of these foreign banks, operating not only in Dubai but also as local entities in various international locations. Consequently, when the initial CSV file was uploaded onto Kepler.gl, the mapping inaccurately included locations in countries such as Iran, Turkey, and Kuwait.

In response to this challenge, we implemented a strategy to refine the geolocation process. Two new columns, City and Address_Plus, were introduced. Address_Plus was created through the concatenation of the Bank Name, Address, and City columns, aiming to provide additional context for the geocoding process. Despite these modifications, the geolocation process encountered persistent challenges, and inaccuracies persisted when uploading the CSV file onto Kepler.gl.

Recognizing the limitations of the initial dataset, a deeper examination was undertaken to understand the intricacies of street naming conventions in the UAE. Recent changes to street names and the prevalence of shared street names across Arab countries contributed to discrepancies within the dataset. Additionally, some streets were named in homage to other Arab countries and notable figures, further contributing to the inaccuracies.

To address these issues, a thorough verification process was initiated. Data was cross-referenced with Google Maps to obtain the most up-to-date addresses for the banks. This process revealed instances where banks had undergone name changes, and certain streets were identified as misspelled. Armed with this corrected information, the geolocation process was repeated, resulting in a successful outcome. All data points were accurately pinned within Dubai, yielding a refined and reliable spatial dataset for our modeling assignment.

In conclusion, the challenges encountered during the geocoding process necessitated a multi-faceted approach. The introduction of additional columns and a meticulous verification process, leveraging external tools like Google Maps, proved instrumental in refining the spatial dataset. This iterative and methodical approach ensures the accuracy and reliability of the geocoded data, providing a solid foundation for subsequent analyses and modeling in the context of our project focused on the banking sector in Dubai.
