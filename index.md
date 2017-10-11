---
format: complete
date: October 2017
title: JB CS:GO Compendium
---


Justus Bersten's CS:GO Compendium
===

## Info
This is my constantly updated CS:GO repository with strats, personal settings and my personal config.

## Author
[STEAM](http://steamcommunity.com/id/phecks/)
[FACE.IT](faceit.com) **inaktiv**
[ESEA.Profile](https://play.esea.net/users/1151692) **inaktiv**

---

## Settings & Config


#### tl;dr version (updated May 2017)
Download config [valve.rc](https://github.com/JustusBersten/abgehen/blob/master/cfg/valve.rc) 


#### Windows 10 Settings
Very good video to get started: [How to setup your PC for CS:GO](https://www.youtube.com/watch?v=HDJPjDg6EsI)

- Windows Sensitivity: 6/11
- Pointer acceleration: OFF
- Mouse: Steelseries Kinzu v2
- Mouse DPI: 400
- Mouse Polling Rate: 1000hz
- Nvidia Settings VSYNC: OFF
- [VibranceGUI by juvlarN](http://vibrancegui.com/) - Ingame Virbance Level 100% (Automated digital Vibrance)
- [Remove XBOX DVR](https://www.youtube.com/watch?v=9MHe2DmjYhc) - Windows 10 Anniversary Update forced CS:GO to run at 30 FPS max. Remove XBOX DVR asap  


#### Launch Options
```
-noforcemparms -noforcemaccel -novid -nojoy -threads 4 -console -tickrate 128 -refresh 144
```
Enter launch options at `Steam > Library > Counter-Strike: Global Offensive (right-click) > Properties > Set Launch Options`


#### Netsettings
The old times of perfectly adjusted netsettings are over (remember 1.6). There is only one standard nowadays:
```
rate "128000"
cl_cmdrate "128"
cl_updaterate "128"
cl_interp "0"
cl_interp_ratio "1"
```


#### Sound 
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


#### Video
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
```


#### Jumpthrow
```
alias "+jthrow" "+jump;-attack"
alias "-jthrow" "-jump"
bind "mouse3" "+jthrow"
```


#### Simple Radar

Click the picture below:
<a href="http://www.simpleradar.com/"><img src="http://www.simpleradar.com/asdf.png" title="Download Simple Radar" style="width: 250px;"/></a>


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
Videos and Links

#### Basics

##### How to play as a team
[Forming a Team](https://www.reddit.com/r/GlobalOffensive/comments/3n29th/csgo_quick_how_to_form_a_team/)
[Kommunikation in Ligaspielen (by HEADSTYLE)](https://github.com/JustusBersten/abgehen/blob/master/headstyle_kommunikation.txt)
[How to become a InGame Leader by gatrcs](https://www.reddit.com/r/GlobalOffensive/comments/6ajd0a/beginners_guide_to_becoming_an_in_game_leader_pt1/)


##### How to play terrorist side
[Strategy for every T-side default](https://www.reddit.com/r/GlobalOffensive/comments/417kah/csgo_strategy_basics_for_t_side/)
[More Basics on T-side](https://www.reddit.com/r/GlobalOffensive/comments/41zbou/guide_to_tside_everyones_invited/)
[Tactical uncommon Bomb plants](http://steamcommunity.com/sharedfiles/filedetails/?id=551826753)

Pistol Round Basics:

- If you lost pistol round
    - and no bomb plant -> force buy tec9s -> if still lost go full eco and buy round 4
    - but planted the bomb -> go full eco round 2 -> buy AKs and full skrilla round 3


#####  Aiming
[Crucial Crosshair Placement](https://www.youtube.com/watch?v=U9mvXfnY8wU)
[How to play the inside lane](https://www.youtube.com/watch?v=DfMvtrc8Ntk)
[launders explains crosshair placement](https://www.youtube.com/watch?v=OfLgNu11EZA)
[How to improve in CS:GO (in depth Guide) by gatrcs](https://www.reddit.com/r/GlobalOffensive/comments/68ywrb/in_depth_guide_on_improving_for_all_levels_of/)
[n0thing on how to spray](https://clips.twitch.tv/MistyEasyWasabiFutureMan)

#####  Movement
[Bunny Hop 2016 onward](https://www.youtube.com/watch?v=yIpURIKhJSs)
[Jump Training Map](https://steamcommunity.com/sharedfiles/filedetails/?l=german&id=314892291)
[Jump Traing Walkthrough (outdated)](https://www.youtube.com/watch?v=9dJ34sUYXyA)
[Launders' Jump School: Long B to tree on Cobble](https://www.youtube.com/watch?v=Zhg2koC94Gg)

#####  Tools
[VAC Checker](https://github.com/MrHayato/VacBanChecker)
[Match History Checker](https://csgostats.gg/)


---


#### Maps

[Very good compilation of 250 smokes for various maps](https://www.reddit.com/r/GlobalOffensive/comments/5t17l0/i_did_nearly_250_smoke_videos/)


##### Cache
[T side Default](http://team-dignitas.net/articles/blogs/CSGO/8531/default-strategies-on-t-side-team-envyus-on-de_cache)
[T Pistol B Strat](https://www.youtube.com/watch?v=g9WfIXWgU5s)
[Taking A Site](https://www.youtube.com/watch?v=i3_WI2OxwyM)
[How to take B](https://www.youtube.com/watch?v=WGaZcqpnGE8)
[B CT Smoke from outside](https://www.youtube.com/watch?v=O7Y6umjCnRc)
[A Site Smoke Quad](https://www.youtube.com/watch?v=rqZTBNC0NKA)
[Wallbang Whitebox](https://www.youtube.com/watch?v=PioblYcMwWc)
[Whitebox Smoke](https://www.youtube.com/watch?v=85z8EQdMuQE)
[B site strat very good](https://www.youtube.com/watch?v=E9d3b-H3o-g)
[10 Self Pop Flashes on Cache](https://www.youtube.com/watch?v=_4tUZPpSWh0)
[70+ tips and tricks](http://imgur.com/a/hIydX)
[A Site Retake Tips by Adren](https://www.youtube.com/watch?v=O4yfLnI_WBU)
[Solo Hold or re-take A from Highway](https://www.youtube.com/watch?v=sAMmjSbjWyg)
[Solo Take A from Squeaky](https://www.youtube.com/watch?v=Z_znfRcdna8)
[Solo Take Mid as T](https://www.youtube.com/watch?v=XvIxQSZrxz4)
[How to pull doors open](https://www.youtube.com/watch?v=0kjipn9pWOI&feature=youtu.be)
[Holding B as CT](https://www.youtube.com/watch?v=hypdmiiPdR8)
[Easy Truck Smoke from Mid (128tick)](https://www.youtube.com/watch?v=gIC-uWvVCjc)
[Re-Smoke Main (many variations)](https://www.youtube.com/watch?v=9-082XlQHlE)
[6 ways to molly Boost](https://www.youtube.com/watch?v=BEcH_5aTC3s)
[3 Mollys for B site (from sunroom)](https://www.youtube.com/watch?v=5ReryZdHxRc)

##### Dust2
[Default Vid by Adren](https://www.youtube.com/watch?v=j8qHbFkzkOU)
[Dust2 Default Slides](https://docs.google.com/presentation/d/1Y_F1F5OBfvsRHCD-nFQYdapCqkItX1ixpj5-YfahBOA/preview?slide=id.p)
[PIZZA NADE - BEST NADE](https://www.youtube.com/watch?v=DvdFGv3JiOU)
[Easy XBOX Smoke for Default](https://youtu.be/FkZ3ECtzSuA?t=43)
[TrilluXe on Long Corner Smoke and XBOX smoke](https://www.youtube.com/watch?v=BYWgzHGY0xI)
[5 Pistol Strats](https://www.youtube.com/watch?v=-0IRGw5WETQ)
[Rush B by Adren](https://www.youtube.com/watch?v=9LkmWXSpr14)
[Rush Cat by Adren](https://www.youtube.com/watch?v=lYCBinRyAyQ)
[Rush Long by Adren](https://www.youtube.com/watch?v=FiN9ZFpWFS0)
[Long A Corner Smoke](https://www.youtube.com/watch?v=bH-W99HtFQE&)
[Dust2 Solo Strategies as T](https://www.youtube.com/watch?v=CKx0n-fIg9c)
[PERFECT long flash](https://youtu.be/mIFKHmg96-g?t=44)
[No Bullshit Tips for DD2](https://www.youtube.com/watch?v=bJ9Ui3eEfM0)
[Must known Smokes for DD2](https://www.youtube.com/watch?v=1agDWlnkPJw)


##### Mirage
[How to throw Smokes on A](https://www.youtube.com/watch?v=0NQjJcqeDl8)
[Smokes A Execute done right](https://www.youtube.com/watch?v=hr0Q2xz2d18)
[B Split Execute](https://www.youtube.com/watch?v=u_V8l58XsR4)
[B Site Smokes](https://www.youtube.com/watch?v=racQWESZQBc)
[40+ tips and tricks](http://imgur.com/a/pOz7Z)
[C9 Force-Buy strat](https://www.youtube.com/watch?v=gpmgDm2b_kU)
[Window Smoke (64 tick)](https://www.youtube.com/watch?v=QTHNvldqOjQ)
[Window Smoke (128 tick)](https://www.youtube.com/watch?v=Tuk64GWXUao)
[NO BS Tips Mirage](https://www.youtube.com/watch?v=PMIjDEpZ_cw)
[Fake Jungle Smoke for Fake A Push](https://www.youtube.com/watch?v=g77S5mbeAsM)
[Fake CT Smoke from Aps](https://gfycat.com/VacantAchingAmbushbug)
[All important smokes from tetris](https://www.youtube.com/watch?v=5ZxqyDYeyT0)
[Resmoke A Ramp from anywhere](https://www.youtube.com/watch?v=ng3WhGvpapE)

##### Cbblestone
[Smokes and Flashes](https://www.youtube.com/watch?v=fvt0bnLuB1E)
[More Smokes and Mollys (updated)](https://www.youtube.com/watch?v=BaKM816ABv8)
[Long B Smoke from CT Spawn (fast)](https://www.youtube.com/watch?v=zdHArZyvzfM)
[Fake Smoke to B](https://gfycat.com/WhichNarrowIndianspinyloach)


##### Train
[Beginner Guide to Train (40min)](https://www.youtube.com/watch?t=40&v=bwzFAYgUJZU)
[Basic Smokes on Train](https://www.youtube.com/watch?v=nWfqVWVa9Og)
[Controlling Ivy](https://www.youtube.com/watch?v=KGy66DEZWT4)
[T-side Pistol](https://www.youtube.com/watch?v=R41GBUaMqkQ)


##### Overpass
[4 important Smokes on de_Overpass](https://www.youtube.com/watch?v=PNCl_u-lx24)
[Monster Strategy](https://www.youtube.com/watch?v=eq0yfdcvKl4)
[Smoke Barrels fast from T Spawn](https://www.youtube.com/watch?v=tcPH3yZDKbs)
[Gulli (Short) Smoke](https://gfycat.com/GlassHighlevelAmericanbadger)


##### Infernew
[6 Smokes](https://www.reddit.com/r/GlobalOffensive/comments/57wunx/6_pug_smokes_to_help_your_life_on_inferno/)
[Banana Control as T](https://www.youtube.com/watch?v=xbNRKq45PTM)
[NO BS Tips Infernew](https://www.youtube.com/watch?v=Kednl8Ugato)
[Adren: 6 most important smokes on infernew](https://www.youtube.com/watch?v=Ivn2nGP6C70)

---

### Contact
Mail: justusbersten@gmail.com
Twitter: [@justusbersten](https://twitter.com/justusbersten)

---
