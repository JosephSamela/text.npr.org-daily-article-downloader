# text.npr.org-daily-article-downloader

This shell script downloads articles from the frontpage of [https://text.npr.org](https://text.npr.org) as individual `.txt` files.

## Setup

Install `wget` and  `lynx` for your distrobution.

```
$ sudo apt install wget lynx
```

## Usage

Run shell script.

```
$ bash fetch-articles.sh
```

Individual articles will be downloaded and written to `.txt` files named with the title of each article. For example...

#### 
```
THE_URL:https://text.npr.org//s.php?sId=734474121 
THE_TITLE:Text-Only NPR.org : As NASA Aims For The Moon, An Aging Space Station Faces An Uncertain Future

Home > Program: Weekend Edition Sunday

   As NASA Aims For The Moon, An Aging Space Station Faces An Uncertain Future
   
   By Nell Greenfieldboyce
   
   Weekend Edition Sunday, · When a rocket carrying the first module of
   the International Space Station blasted off from Kazakhstan in November
   of 1998, NASA officials said that the station would serve as an 
   orbiting home for astronauts and cosmonauts for at least 15 years.
   
   It's now been over 18 years that the station has been continuously                                         
   occupied by people. The place is impressive, with more living space
   than a six-bedroom house, two bathrooms and a large bay window for
   looking down at Earth.
   
   NASA and its international partners have spent decades and more than
   $100 billion to make the station a reality. The trouble is, as the
   agency sets its sights on returning people to the moon, the aging
   station has become a financial burden. And it's not clear what its
   future holds.                                           
```
