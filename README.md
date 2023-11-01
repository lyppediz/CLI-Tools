# My CLI Tools

## :mag_right: Internet Explorer:
### lynx
	sudo apt install lynx

## :open_file_folder: Manager Explorer:
### ranger
	sudo apt install ranger

## :vhs: Video Downloaders:
### yt-dlp
	sudo wget https://github.com/yt-dlp/yt-dlp/releases/latest/download/yt-dlp -O /usr/local/bin/yt-dlp
    
	sudo chmod a+rx /usr/local/bin/yt-dlp
    
	yt-dlp -U

### gdl gdrive-downloaders
	curl -Ls --compressed https://github.com/Akianonymus/gdrive-downloader/raw/master/install.sh | sh -s
    
	echo '[ -f "${HOME}/.gdrive-downloader/gdl" ] && [ -x "${HOME}/.gdrive-downloader/gdl" ] && PATH="${HOME}/.gdrive-downloader:${PATH}"' >> ~/.bashrc

## :floppy_disk: General downloaders
### wget
	sudo apt-get install wget
	
### curl
	sudo apt-get install curl

## :card_file_box: Others

### cmus (music player)
	sudo apt-get install cmus
	
### ffmpeg (video and audio converter)
	sudo apt-get install ffmpeg
