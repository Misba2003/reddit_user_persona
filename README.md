                                                                        Reddit User Persona Builder

Overview
This project Scrapes a Reddit user’s recent comments and posts using the PRAW (Python Reddit API Wrapper) library.
It then generates a user persona summary based on their public activity, including interests, writing style, and personality traits with specific citations from their posts and comments.

Technologies used
-	Python
-	PRAW
-	Google Colab

How to run
1.	Install required packages
-	!pip install praw

2.	Create a Reddit API application 

-	Visit https://www.reddit.com/prefs/apps.
-	Click “create app”
-	Choose type: Script
-	Set redirect URL: http://local host:8080
-	Click create app
-	Copy your client_id and client_secret

3.	 Update the credentials in the script 

-	Client_id= “Your client_id”
-	Client_secret= “Your client_secret”

4.	 Change the target username
   
-	Username= “Kojied”

5.	Run the script 
-	It will generate a raw text file containing recent comments and posts.
-Then, read the file and write a persona summary manually (as done in this project)
-	Save the persona summary as .txt file, citing comments and posts to support each trait

 Files
-	Reddit_User_Persona_Builder: Main colab notebook containing all code
-	Kojied_persona.txt : Persona summary for user kojied.
-	Hungry-Move-6603_persona.txt: persona summary for Hungry-Move-6603
-	Kojied_raw_text.txt: Raw scrapped data for kojied.
-	Hungry-Move-6603_raw_text.txt : Raw scrapped data for Hungry-Move-6603

  Notes:
The final persona summaries are manually written after analyzing scraped data to ensure human level insight and accuracy
This project encourages a mix of automation (data scraping) and critical human analysis (persona creation), as specified in the assignment.

More about the assignment:

-Initially, I attempted to use OpenAI’s GPT API to automatically generate the persona summaries from the scrapped text.
-Due to quota limitation on the API key, I was unable to include this automated step in the final version
-The current version therefore includes manual persona summaries, as also allowed in the assignment instructions
-The code framework for integrating an LLM can be added easily in the future for providing an active OpenAI API key.


Contact:
+91 9224591849
misbayadgiri786@gmail.com
Regards,
Misba Yadgiri








































