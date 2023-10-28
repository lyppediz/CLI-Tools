## **My CLI Tools**

## Internet Explorer:
### lynx
    sudo apt install lynx

## Manager Explorer:
### ranger
    sudo apt install ranger

## Video Downloaders:
### yt-dlp
    sudo wget https://github.com/yt-dlp/yt-dlp/releases/latest/download/yt-dlp -O /usr/local/bin/yt-dlp
    
    sudo chmod a+rx /usr/local/bin/yt-dlp
    
    yt-dlp -U

### gdl gdrive-downloaders
    curl -Ls --compressed https://github.com/Akianonymus/gdrive-downloader/raw/master/install.sh | sh -s
    
    echo '[ -f "${HOME}/.gdrive-downloader/gdl" ] && [ -x "${HOME}/.gdrive-downloader/gdl" ] && PATH="${HOME}/.gdrive-downloader:${PATH}"' >> ~/.bashrc

## Others
- wget
- cmus
- awk
- grep
- exiftool
- ffmpeg
