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
	-s [valye]	: 1 - Will be downloaded to current directory.
		 	: 2 - Will download as root and save in /usr/local/bin"
	   : After setup, usage 1: ./youtube-dl-playlist [optional options] [playlist url]
				2: youtube-dl-playlist [optional options] [playlist url]

example:
	youtube-dl-playlist [playlist url] - Will download playlist to current directory without auto numbering (default)
	youtube-dl-playlist -s 1 - Will download youtube-dl to current directory and you use it with ./
	youtube-dl-playlist -d [path to directory] [playlist url] - Will download playlist to specified directory
	youtube-dl-playlist -a 1 [playlist url] - Will download to current directory and number your videos on [1,2,3,4,...]
	youtube-dl-playlist -d [path to directory] -a 01 [playlist url] - Will download to given path with numbering [01,02,03,...]

This script uses youtube-dl which is property of https://ytdl-org.github.io/youtube-dl/about.html 

For all complete info on how to use youtube-dl visit https://github.com/ytdl-org/youtube-dl
Again, I take no credit whatsover for the development of youtube-dl, I just got some request on a script to auto download a playlist

