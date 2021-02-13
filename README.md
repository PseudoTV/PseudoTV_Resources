# PseudoTV_Resources

Resource media `images, videos`

Resource type `overlays, logos, ratings, bumpers, commercials, trailers`

Naming schema `resource.media.type.collection_name` ex.`resource.images.logos.retro_70s`

Formats:
  images: `json,png,gif,jpg,xbt`
  video: `json,avi,mkv,mp4,mpg`

https://forum.kodi.tv/showthread.php?tid=347359


# Resource Folder Structure

resource.images.logos.sample/
├── resources/
│   ├── ABC.jpg
│   ├── CBS.png
│   └── NBC.gif

resource.videos.bumpers.sample/
├── resources/
│   └── ABC (Channel Name)
│       ├── 1.mpg
│       ├── ABC.mkv
│       ├── ABC.avi
│       └── Commercial.mp4

resource.videos.ratings.sample/
├── resources/
│   ├── TV-MA.mpg
│   ├── NC-17.mkv
│   ├── G (3DSBS).avi
│   └── R.mp4

resource.videos.commercials.sample/
├── resources/
│   └── ABC (Channel Name)
│       ├── 1.mpg
│       ├── ABC.mkv
│       ├── ABC.avi
│       └── Commercial.mp4

resource.videos.trailers.sample/
├── resources/
│   └── Action (Channel Genre)
│       ├── 1.mpg
│       ├── Action.mkv
│       ├── Action.avi
│       └── trailers.mp4
          
*Root (resources/) folder added to all channels.
**Folders are cap-insensitive, However must match channel name as it appears in guide.
*** 3D ratings supported, requires "(3DSBS)" prefix.
**** Animated *.gifs supported for logos.
***** *.json format for video download utility. 