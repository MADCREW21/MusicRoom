# MusicRoom
SRS

SRS
Definitions:
	Users:
Requester: a user who can solely provide information for song request
Regulator: the administrative user of a given room who controls the songs played and has typical requester privileges

Executive Summary:
	The intention of this project is to create a program that enables classrooms or groups of people to listen to music appropriate to how they feel. On the creation of a group, the user creating the group will have regulator privileges (discussed below), and will be able to share a link to anyone else who has interests in listening with this created group. These invited individuals (denoted as requesters to be discussed below) and the regulator will have access to the group’s playlist determined by their own suggestions, with the playlist being monitored and altered by the regulator.
	As a requester, one has the ability to select from an assortment of adjectives and factors to describe what they want to listen to and/or how they feel. As a result, songs will be chosen from a collection of playlists gathered off of Spotify.
	As a regulator, one has the abilities mentioned above in the description of a requester’s privileges but can also cancel any queued-up songs, and, considering that each member will be together, only the regulator will be able to connect to the audio of the playing song. This means that the regulator is the only individual who can pause, unpause, and even skip current songs. All of the aforementioned is meant to allow the regulator to push for an optimal workflow or ambience based on their own analysis of their surrounding requesters and themselves.

Categorized Functionalities: 
Functional Requirements:
Users must be able to create and join independent rooms (organized similarly to a multi-room chat room service)
Users must have different abilities determined by whether they create a new room or join an existing one
One who creates a room must have “regulator” and “requester” based privileges/accessibilities
One who joins a room can only have “requester” based privileges/accessibilities
Each user will be able to select a or maybe even type in a song title) in order to add a song to the room’s playlist (this is a “requester” privilege)
Upon given these factors, the server must search through a collection of songs and find a viable songs to play that meet the criteria given within each room
Upon finding a song, the server must store the song title in something similar to an array (if not just an array) for each room
Only regulators moderate and modify a room’s playlist
Only regulators can play, pause, resume, and skip songs (sound and sound control for any particular room occurs only on the regulator’s side)
When no song is playing, a song finishes or a song is skipped, the next song in the playlist must start
Non-Functional Requirements:
Members of “Mad Crew” must make sure to put effort into their respective work/side of the project, ask for help when necessary, and be willing to help other members
Interface Requirements:
The home page will allow people to join available rooms via a room code/password or create a new room
Upon entering a room (new or previously made), a user will be able to see the current list of songs for that room’s group of users
Each user in a room will have a section of their screen dedicated to making a song request (discussed above)
Regulators can see icons indicating and allowing their abilities to remove songs from the playlist, as well as pause, resume, and skip the current song
Colors/Themes must be appealing but not excessive

Team Roles:
	Pallavi:  Backend
	Asher:  UI/UX/Frontend
	Eric:  UI/UX/Frontend
	Hunter:  Backend
