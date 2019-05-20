This script auto downloads youtube videos. It uses youtube-dl located at https://github.com/ytdl-org/youtube-dl

Therefore I take no credit for the tool used to download the video, I merely as per request by most of my people

created a script to auto download a playlist to a given directory

script usage:
	- ./youtube-dl-playlist [optional options] [playlist url]

	- by default it downloads to the current directory you are at

options:
	-a [value] : Is auto number. If you want your videos to be numbers in the way they appear on your tube
		[value] is a number at which the download will number your videos
		recommended value is 1 = 1,2,3,4...
		Anyvalue looks like: 01 = 01,02,03...
	-d [directory]: Is the directory you want your videos to be saved when downloading (default is current)
	-s : setup, pushes the script to system allowing it be called directly from the terminal without path
	   : After setup, usage : youtube-dl-playlist [optional options] [playlist url]

This script uses youtube-dl which is property of https://ytdl-org.github.io/youtube-dl/about.html 

For all complete info on how to use youtube-dl visit https://github.com/ytdl-org/youtube-dl
Again, I take no credit whatsover for the development of youtube-dl, I just got some request on a script to auto download a playlist

