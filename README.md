# Music Plyayer App API

This API is for the [Music Player](https://github.com/iknowahra/musicPlayer/). It sends simple music album data

## how to set up

```bas
$ npm install
$ npm start
```



Basically this API uses port 5000. If you visit to 'http://localhost:5000/musics', you will meet data below.

```json
{
  "musics":[
  {
    "title":"19th Floor",
   "artists":["Bobby Richards"],
   "cover":"covers/19th_floor.png",
   "source":"musics/19th Floor - Bobby Richards.mp3",
   "vote":3534
  },
  {"title":"Sunny Travel",
   "artists":["Nico Staf"],
   "cover":"covers/sunny_travel.png",
   "source":"musics/Sunny Travel - Nico Staf.mp3",
   "vote":123987
  }, 
    
    ... 
    
]}; 
```



This API doesn't provide any image or music files but only path of assets of client. You should edit `./db/db.json` file if you want to use other url.

