# 3SpaceCows
also siezed by the FFBI // inside Joke


README

///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
Team members (3)
///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

Carlos Patino - 	@Vily3
Designed the back end, called ChatGPT to help create starting code for using an API key for Gemini to talk to it. Used Regex as a pattern recognision to find the specified information to scrape.


Rose C. - Beginner	@GlitchTheWitch
Made the art used for the program, helped design the idea to turn the application into a webpage that could be used on a phone with the Event pass


Jose - Beginner	@chromedreamer
Created the front end with the help of Gemini, and going through and making sure the API key was still being used and could communicate to it from the program. Along with debugging for the front end.


///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
Inspiration
///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////


we wanted to make something simple that still implemented AI, and clearly showed our individual abilities, and our capability as a group.

Some of our first ideas:

- saloon AI drinking game
	- everyone you talk to is an AI
	- maybe implement a miniature server that everyone at the hack-a-thon could join, and would have a hard time telling them apart from actual people

- space cowboy tycoon game
	- defend farm from shark-natos
	- cows can just float away
	- cow hearing 

- phishing detection
	- would not be very easy to implement as a first time hack
	- might be hard to make the front-end UI on theme

- AI recipe generator
	- cowboy speech?
	- from personal experience the recipies tend to not be good if too many restrictions are added during the AI promt

- AI cowboy themed cow-lander (calendar)

- space cowboy name generator
	- be given a name, hard code certain titles, and something akin to pig-Latin
		- (as in add syllables that still make the correct phonetic sound)
	- then send to AI to give it some extra flare



In the end we started with the last idea of the NameGenerator. After getting decently far into it we realized that we could also apply the guild's everyone was a part of to add further elements that could be sent to an AI.

Once we got to a point where we could Add any name and some guild (including one incase the user chose an invalid one). we decided to see if we could attempt to somehow get that info from the Event pass that everyone had which had all that information.


///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
Technologies used
///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////


- Gemini
	- The AI (API) that is given the Name, Guild, and a randomly chosen prompt to create a short story for the user
	- helped to start the front end 

- ChatGPT
	- Helped start the code specifically for calling the Gemini AI though a specified manually added API key
	- helped in finding a potential way to utilize the camera on a phone/laptop to scrape the information that would be used for the app (Name, and Guild)

- OpenCV
	- used specifically to access the camera

- Tesseract OCR
	- to extract the visible text before using Regex to extract the specific text we wanted


///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
If we had more time
///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

If we had more time I (Carlos) would want to keep working on the Camera and to be able to take a picture of the Event Pass directly
