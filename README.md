mep-feature-playlist -  A playlist plugin for MediaElement.js
=
Usage:

1 - Download **[MediaElement.js] (http://mediaelementjs.com/)**

2 - Download **[mep-feature-playlist] (https://github.com/duozersk/mep-feature-playlist/archive/master.zip)**

3 - Include

- **mediaelement-and-player.js**
- **mediaelementplayer.min.css**
- **mep-feature-playlist.js**
- **mep-feature-playlist.css**

4 - Add this code to your page:

    <script>
    $(function(){
        $('audio,video').mediaelementplayer({
            alwaysShowControls:false, 
            features: ['playlistfeature', 'prevtrack', 'playpause', 'nexttrack', 'loop', 'shuffle', 'playlist', 'current', 'progress', 'duration', 'volume']
        });
    });
    </script>
    
- **playlistfeature** - general feature to enable playlist functionality; it just builds the internal playlist layer, it should be present if you want to use playlist
- **prevtrack** - button to play the previous track in the playlist
- **nexttrack** - button to play the next track in the playlist
- **loop** - toggle to turn repeat on or off
- **shuffle** - toggle to turn shuffle on or off - DOESN'T WORK YET
- **playlist** - playlist button to show/hide playlist

5 - Add the audio tag and your tracks:

    <audio controls="controls" autoplay="autoplay">
        <source src="media/AirReview-Landmarks-02-ChasingCorporate.mp3" title="Chasing Corporate" type="audio/mpeg"/>
        <source src="media/framing.mp3" title="Framing" type="audio/mpeg"/>
    </audio>


NOT UPDATED SECTIONS
=
Screenshots

**Default Collapsed**

When the player is loaded with the **playist** feature, it will add playlist toggle button along with **next** and **previous** buttons.

![MEjs Collapsed playlist](http://jq.thebrandcrew.com/garage/mep-feature-playlist/img/playlist_collapsed.jpg "MEjs Collapsed playlist")


**Playlist Expanded**

![MEjs Expanded playlist](http://jq.thebrandcrew.com/garage/mep-feature-playlist/img/playlist_expanded.jpg "MEjs Expanded playlist")

**While Playing**

![MEjs Playing](http://jq.thebrandcrew.com/garage/mep-feature-playlist/img/playlist_expanded_playing.jpg "MEjs Playing")


More options and installation instructions related to MediaElementjs itself can be found [here] (http://mediaelementjs.com/#installation).

###[Demo] (http://projects.junaidbaloch.com/mep-feature-playlist/)
