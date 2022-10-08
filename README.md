<h1 style=italic align=center>―――― { 𝓟𝓸𝓵𝔂𝓫𝓪𝓻 𝓣𝓱𝓮𝓶𝓮𝓼 } ――――</h1>

<p align="center">

<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/prcxzm/polybar-themes?color=a3b8ee&labelColor=1e2122&style=for-the-badge">
<img alt="GitHub forks" src="https://img.shields.io/github/forks/prcxzm/polybar-themes?color=efaee0&labelColor=1e2122&style=for-the-badge">
<img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/prcxzm/polybar-themes?color=abb2bf&labelColor=1e2122&style=for-the-badge">

</p>

#  `ᴅᴇᴘᴇɴᴅᴇɴᴄɪᴇꜱ` 

  * **[Nerd Font](https://www.nerdfonts.com/)**
  * **[Material Font](https://github.com/daimoonis/material-icons-font)**

#  `ᴘᴏʟʏʙᴀʀ ᴛɪᴘꜱ` 

<details>
  <summary><b>Enable Shadow</b></summary>
  <br>
  
  If you wanted to add shadow on Polybar, you can add this config to your `picom.conf`
  
  > i don't use compton or another compositor.

``` sh
wintypes:
{
  tooltip = { shadow = true; opacity = 0.75; full-shadow = false; };
  dock = { shadow = true; full-shadow = false; }
};
```
  
and also, set `no-dock-shadow` to `true` on `picom.conf`
  
``` sh
no-dock-shadow = true;
```

</details>

<details>
  <summary><b>Disable Shadow</b></summary>
  <br>
  
  If you want to disable shadow on Polybar, just simply make them to `false`
  
``` sh
wintypes:
{
  tooltip = { shadow = false; opacity = 0.75; full-shadow = false; };
  dock = { shadow = false; full-shadow = false; }
};
```
``` sh
no-dock-shadow = false;
```
  
</details>

# `ᴄᴏʟᴏʀsᴄʜᴇᴍᴇs`
 
> <p><i>colorschemes that i use for my own Polybar Themes</i></p>
 
  - [onedark](https://github.com/joshdick/onedark.vim)
  - [nord](https://www.nordtheme.com/)
  - [catpuccin](https://github.com/catppuccin/catppuccin)
  - [tokyonight](https://github.com/folke/tokyonight.nvim)
  - [everblush](https://github.com/Everblush/everblush)
  
> <p><i>other colors is customized by me</i></p>
  
# `ᴛʜᴇᴍᴇs`

# ᴛᴏᴋʏᴏ
![tokyo](https://user-images.githubusercontent.com/88080186/184541233-80996ea9-6135-4399-8bc8-f33f791cc2ac.png)


# ɴᴇᴏɴ
![neon](https://user-images.githubusercontent.com/88080186/192147185-518275d7-f4a8-4dbc-9333-ec0e3920fd26.png)


# ᴄᴀɴᴅʏ
![candy](https://user-images.githubusercontent.com/88080186/192133204-ed48dc2e-5cd0-404b-a7d1-c37247d449be.png)


# ɴᴏʀᴅɪᴄ
![nordic](https://user-images.githubusercontent.com/88080186/151793475-46fabd9f-50d2-49df-a892-45b91ab25d56.png)


# ᴍɪᴅɴɪɢʜᴛ
![midnight](https://user-images.githubusercontent.com/88080186/192132293-fcc3c565-be20-49e8-8282-87fb22064d87.png)


# sɪᴍᴘʟᴇ
![simple](https://user-images.githubusercontent.com/88080186/192145038-35814622-dcda-40b3-9df7-b2ca17f763d0.png)


# ᴘɪɴᴋʏ
![pinky](https://user-images.githubusercontent.com/88080186/148096412-94aa4137-c836-4106-aa13-8d9ae5cba61a.png)


# sʟɪᴍ
![2022-09-24_22-40](https://user-images.githubusercontent.com/88080186/192104229-05ee3961-bfca-43d4-95cb-ed0fec6d9d99.png)



# `ᴄʟᴏɴᴇ`
``` sh
git clone https://github.com/prcxzm/polybar-themes

```
> some of my polybar themes are inspired by [siduck](https://github.com/siduck/dotfiles) & [adi1090x](https://github.com/adi1090x/polybar-themes)
