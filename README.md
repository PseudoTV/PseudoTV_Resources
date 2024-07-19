

# PseudoTV_Resources

Resource media `images, videos`

Resource types `overlays, logos, ratings`

Naming schema `resource.media.type.collection_name` ex.`resource.images.logos.retro_70s`

Formats:
 - images: `json,png,gif,jpg,xbt`
 - video: `avi,mkv,mp4,mpg`

[Kodi Forum Thread](https://forum.kodi.tv/showthread.php?tid=347359)


# Resource Folder Structure

    resource.images.logos.sample/
    ├── resources/
    │   ├── ABC.jpg
    │   ├── CBS.png
    │   └── NBC.gif

    resource.videos.ratings.sample/
    ├── resources/
    │   ├── TV-MA.mpg
    │   ├── NC-17.mkv
    │   ├── G (3DSBS).avi
    │   └── R.mp4

    resource.videos.bumpers.sample/
    ├── resources/
    │   ├── Foo.avi
    │   ├── Bar.mkv
    ├── BBC/
    │   ├── Foobar.mkv
    ├── Drama/
    │   ├── Foobar.mkv

    resource.videos.adverts.sample/
    ├── resources/
    │   ├── Foo.avi
    │   ├── Bar.mkv
    ├── BBC/
    │   ├── Foobar.mkv
    ├── Drama/
    │   ├── Foobar.mkv

    resource.videos.trailers.sample/
    ├── resources/
    │   ├── Foo.avi
    │   ├── Bar.mkv
    ├── BBC/
    │   ├── Foobar.mkv
    ├── Drama/
    │   ├── Foobar.mkv

    *    Root (resources/) folder added to all channels.
    **   Folders are not cap-sensitive, However must match channel name and genre as it appears in guide.
    ***  Animated *.gifs supported for logos.
