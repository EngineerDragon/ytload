# Ytload - basic cli to download or search videos
## Usage : 
ytload [options] [action]  ... \
Actions: \
   download                         Downloads the specified link as specified format. \
   search                           Searches for the specified string. \
   info                             Gets the video of the specified link \
Options: \
  -h, --help                        Shows the help directory \
  -d [DIR], --installdir=DIR        Sets the install directory. \
  -v, --version                     Prints the current version of the program. \
  -m, --mp3                         If download is selected get the video as a mp3 file. \
  -l [LINK], --link=LINK            Link argument for actions. \
  -q [QUERY], --query=QUERY         Query argument for search. 

### Some example usages : 
```bash
ytload search Disfigure blank
ytload --link="https://www.youtube.com/watch?v=dQw4w9WgXcQ" --mp3 download
ytload --link="https://www.youtube.com/watch?v=dQw4w9WgXcQ" info
```

#### Some extra notes :
I did not implement the mp3 part yet I probably will implement it in the future \
I probably will implement the --link as direct argument 