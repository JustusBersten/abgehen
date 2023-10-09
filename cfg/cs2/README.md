
# CS2 Config

## Settings & Config

### Specific binds
I am using custom binds for years. If you use this config make sure you read which binds might needs change for your liking!

```
bind "c" "player_ping" // Default MOUSE3
bind "f" "+use" // Default e
bind "t" "use weapon_c4; drop" // custom
bind "x" "use weapon_knife; use weapon_flashbang" // custom
bind "enter" "say k" // beeing cool in 2008
```

### Buy script
I use a custom buyscript that utilizes numpad.

```
// BUYSCRIPT
bind "KP_1" "buy incgrenade;buy molotov"
bind "KP_2" "buy p90; buy vest"
bind "KP_3" "buy galilar; buy famas; buy vest"
bind "KP_4" "buy ak47; buy m4a1; buy vesthelm"
bind "KP_5" "buy awp"
bind "KP_6" "buy smokegrenade"
bind "KP_7" "buy flashbang"
bind "KP_8" "buy defuser"
bind "KP_9" "buy vest;buy vesthelm"
bind "KP_DEL" "cl_righthand 1;timeleft"
bind "KP_DIVIDE" ""
bind "KP_MULTIPLY" "buy hegrenade"
bind "KP_enter" ""
bind "KP_PLUS" ""
bind "KP_MINUS" ""
bind "KP_0" ""
```


### Download & installation
[valve.rc](https://raw.githubusercontent.com/mjt91/abgehen/master/cfg/cs2/valve.rc)

1. Navigate to: `C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\core\cfg`
1. Open `config.cfg` and ***DELETE*** all content.
1. Save the empty file and make it ***READ ONLY***
1. Create a new .txt file and name it `valve.rc`
1. Open the file with your favourite text editor.
1. Click the Link above and copy & paste my config.
    - *Optional:* Make this file ***READ ONLY*** too. (I am not sure if this is a must or optional. Sometimes CS F***S YOU OVER AND OVERWRITES ALL YOUR CONFIG FOR NO REASON).
1. Start the game. Open Console. You should see an echo message.
    - If this is not the case run `exec valve.rc` into the console and you should be good to go.

___


### Windows 10 Settings
Very good video to get started: [How to setup your PC for CS:GO](https://www.youtube.com/watch?v=HDJPjDg6EsI)

- Windows Sensitivity: 6/11
- Pointer acceleration: OFF
- Mouse DPI: 400
- Mouse Polling Rate: 1000hz
- Nvidia Settings VSYNC: OFF
- [VibranceGUI by juvlarN](http://vibrancegui.com/) - Ingame Virbance Level 100% (Automated digital Vibrance)


Windows 10 Anniversary Update forced CS:GO to run at 30 FPS max.
My guess is that this is not relevant for CS2 anymore.
Otherwise: Remove XBOX DVR asap!
- [Remove XBOX DVR](https://www.youtube.com/watch?v=9MHe2DmjYhc) 


### Launch Options
```
-high -noforcemparms -noforcemaccel -novid -nojoy -threads 4 -console -tickrate 128 -refresh 144
```
Enter launch options at `Steam > Library > Counter-Strike 2 > right-click > Properties > Set Launch Options`


### Netsettings
The old times of perfectly adjusted netsettings are over (remember 1.6). There is only one standard nowadays:

```
rate "128000"
cl_cmdrate "128"
cl_updaterate "128"
cl_interp "0"
cl_interp_ratio "1"
```


### Sound 
Good read to get started: [Guide to Sound](https://www.reddit.com/r/GlobalOffensive/comments/3zqtvm/improved_csgo_sound_why_the_popular_settings_suck/)

**IMPORTANT: DISABLE HRTF with snd_use_hrtf 0**

```
snd_use_hrtf "0"
snd_musicvolume "0"
snd_mixahead "0.05"
dsp_enhance_stereo "0"
windows_speaker_config "1"
snd_front_headphone_position "45.0"
snd_rear_headphone_position "90.0"
snd_headphone_pan_exponent "1.2"
snd_headphone_pan_radial_weight "0.5"
```


<!-- #### Video
After the Wild West Simulator 2015 update, [_video.txt_](https://github.com/JustusBersten/abgehen/blob/master/cfg/video.txt) needs to be put in `..\Steam\userdata\<Steam3 ID>\730\local\cfg`

```
"VideoConfig"
{
    "setting.cpu_level"     "0"
    "setting.gpu_level"     "0"
    "setting.mat_antialias"     "0"
    "setting.mat_aaquality"     "0"
    "setting.mat_forceaniso"        "0"
    "setting.mat_vsync"     "0"
    "setting.mat_triplebuffered"        "0"
    "setting.mat_grain_scale_override"      "1"
    "setting.gpu_mem_level"     "0"
    "setting.mem_level"     "2"
    "setting.mat_queue_mode"        "-1"
    "setting.csm_quality_level"     "0"
    "setting.mat_software_aa_strength"      "0"
    "setting.mat_motion_blur_enabled"       "0"
    "setting.fullscreen"        "1"
    "setting.defaultres"        "1440"
    "setting.defaultresheight"      "1080"
    "setting.aspectratiomode"       "0"
    "setting.nowindowborder"        "0"
}
``` -->


### Jumpthrow

**Note: With the CS2 update, this bind is not needed anymore! Jumpthrow nades are consistent now. However, if you are used to use a jumpthrow as I am, I would keep it.**

```
// JUMPTHROW
alias "+jumpaction" "+jump;"
alias "+throwaction" "-attack; -attack2"
alias "-jumpaction" "-jump"
bind MOUSE3 "+jumpaction;+throwaction;"
```


#### Radar Settings

- Personal radar settings, but purely preference.

```
cl_radar_always_centered "1"
cl_radar_scale "0.35"
cl_hud_radar_scale "1.15"
cl_radar_icon_scale_min "1"
cl_radar_rotate "1"
cl_radar_square_with_scoreboard "0"
```


---


### Strats
Videos and links


####

[5 Smokes for every map](https://www.youtube.com/watch?v=LBzuOB3C4TY)


#### Basics

##### How to play as a team
[Forming a Team](https://www.reddit.com/r/GlobalOffensive/comments/3n29th/csgo_quick_how_to_form_a_team/)
[Kommunikation in Ligaspielen (by HEADSTYLE)](./data/headstyle_kommunikation.txt)
[How to become a InGame Leader by gatrcs](https://www.reddit.com/r/GlobalOffensive/comments/6ajd0a/beginners_guide_to_becoming_an_in_game_leader_pt1/)


##### How to play terrorist side
[Strategy for every T-side default](https://www.reddit.com/r/GlobalOffensive/comments/417kah/csgo_strategy_basics_for_t_side/)
[More Basics on T-side](https://www.reddit.com/r/GlobalOffensive/comments/41zbou/guide_to_tside_everyones_invited/)
[Tactical uncommon Bomb plants](http://steamcommunity.com/sharedfiles/filedetails/?id=551826753)

Pistol Round Basics:

- As CT never buy defuse (data shows it is not worth it)
- If you lost pistol round
    - and no bomb plant -> force buy tec9s -> if still lost go full eco and buy round 4
    - but planted the bomb -> go full eco round 2 -> buy AKs and full skrilla round 3

