# Introduction

This repo serves 2 main purposes:

1. a place for me to write down my keyboard journey and thus a tool for thinking
2. A forum where my friends who share my keyboard obsession can help me progress and choose when I feel unsure or overwhelmed. These friends are currently distributed across various slacks, forums, etc and I want a personal place to gather their input. I call these my "keyboard therapists". The pay is not good.
3. Ultimately I'd like to write or contribute to a comprehensive guide

# v0 (1990s)

- Improper 6-finger qwerty touch typing
- assorted early Windows and Mac desktops and laptops

# v1 (2000s)

- Learned proper 10-finger touch-typing and the dvorak layout
- Still on standard keyboard hardware
- transitioned from mostly-mac to mostly-linux
- set keyboard layout with OS utilities
- `setxkbmap dvorak` but not much beyond that

# v2 (2010s)

- Stabilized for a while on macbook pro with dvorak in software and Keyboard Maestro
- Developed first extensive snippets library. Worked throughout the GUI session.
- Developed large toolbox of macros in Keyboard Maestro
- Remapped caps lock to control via macos keyboard settings
- Enabled OSX "Sticky Keys" accessibility setting for one-shot modifiers
  - For several years was convinced all modifiers should be one-shot and chording was terrible
  - This partially hinged on how great and reliable macos GUI/HUD overlay was. Whenever a sticky modifier was activated, there was clear indication on the screen

# v3.0 (2013)

- Bought an ergodox in I think the 2nd massdrop group buy
- full-hand acrylic case
- became a true believer in
  - split keyboards
  - ortholinear layout
  - thumb clusters
  - steep tenting
  - multilayer layouts
- Layers evolved frequently but the core bits were
  - Base layer still qwerty and doing dvorak remapping in the OS
    - Tried also dvorak in firmware and switching between external and laptop keyboard requires changing the OS input layout and it's a hassle. Easier to just always do dvorak in the OS.
  - Navigation/formatting layer
  - Numpad layer on right hand
  - Weird but good columns for paired punctuation: `() {} []`
- Was not explicitly aware of QMK at this point. Not managing my ergodox configuration in git, etc.
  - Using keyboard-layout-editor.com and configure.ergodox-ez.com

# v3.1 (2018)

- Bought an Infinity Ergodox
- Learned about Quantum Mechanical Keyboard (QMK) project
- Discovered more subreddits like /r/mechanicalkeyboards, /r/ergomechanicalkeyboards, /r/olkb
- adopted QMK tooling for both my ErgoDox and Infinity ErgoDox
- Learned about mod-taps via Ross Hadden and started using them via `xcape` on linux
- Added some mod-taps to my QMK layers

# v3.2 (2020)

- Bought and tried a keyboardio model 01
- The large pinkie column offset was too different from the ergodox (and standard keyboards) for me to adjust to
- I ended up typing one row too high on the pinkie column by accident
- at some point may give it another go, but at that time I gave up and switched back to my ergodoxes

# v3.3 (2020)

- Learned about kmonad and started to replace my linux X11 utilities (setxkbmap, xmodmap, xbindkeys, xcape) with kmonad for thinkpad linux laptop keyboard stuff
- Tried home row mod-taps
- Had to use macos/macbook for work
  - Researched extensively for tools for snippets, macros, hotkeys, etc
  - settled on hammerspoon, karabiner elements, and bettertouchtool as key components of my macos stack
- Nicely scripted QMK compiling/flashing
- Using ergodox on linux and infinity ergodox on mac

# v4 (2020)

- Thinking about buying/building another fancy keeb but not quite ready for hand wiring, custom PCBs, full-on late-game project yet. Something achievable in a few weekends
- Honestly the ergodox is still mostly working great
- CONTENT WARNING: MECHANICAL KEYBOARD ENTHUSIAST BLASPHEMY BELOW
- Stop reading now if you are all about the click
- Some minor motivations
  - Would like lower-travel keys
    - I find a lot of my strain and slowness is how far I have to lift my fingers back up after pressing a key with a lot of travel
    - generally I prefer the switches in my thinkpad
  - My ergodox keys have a ping sound on release that I don't like
  - I'd like lowest available activation force
  - I'd like as close to silent as possible
- My main gripe with most ortholinear split keebs I see on reddit is the thumb cluster
  - Some don't have one at all. GTFO.
  - Most put 2 or 3 "thumb" keys under the palm of the hand. I have no idea why but I absolutely hate that. It's my #1 gripe with regular keyboards by far that there are modifier keys inaccessible under the palm of your hand.
  - Ones that actually have keys near the thumb only have 1 or 2 often
  - I think I need at least 3 but could easily put 5 or 6 to good use
- I kind of want something that might be easier to mount directly over the top of my thinkpad built-in laptop. Maybe something [like this](https://www.reddit.com/r/MechanicalKeyboards/comments/jkcbud/white_on_black_on_silver_on_laptop_introducing/)

## v4 Possibilities

### kyria

![kyria](https://i.imgur.com/dvI4KcU.jpeg)

[reddit post](https://www.reddit.com/r/ErgoMechKeyboards/comments/jh69s3/my_first_diy_keyboard_build_kyria/)

![kyria](https://external-preview.redd.it/imTeK5An1wr_O_9gtHY2Xubv2LuwESBO7Z-oL-Mea0o.jpg?width=960&crop=smart&auto=webp&s=b6c30dfa0331b98848fe4f4c5fa41a91ee12757f)

[reddit post](https://www.reddit.com/r/ErgoMechKeyboards/comments/jhctfw/never_shared_my_build_before_and_now_seemed_like/)

![kyria](https://preview.redd.it/k16qtlnvlup51.jpg?width=960&crop=smart&auto=webp&s=82efe94bdae5459c9ed2456dd023a2a35e3e2bf3)

[reddit post](https://www.reddit.com/r/ErgoMechKeyboards/comments/j1877x/kyria_at_his_minimum/)

### redox with choc

![redox](https://i.imgur.com/ZTlHb72.jpg)

[reddit post](https://www.reddit.com/r/ErgoMechKeyboards/comments/ji78bd/low_profile_choc_redox/)

### iris v4

![](https://preview.redd.it/pxqlpivu3gu51.jpg?width=960&crop=smart&auto=webp&s=e99b66bf5082d95a4747cdda3004f16fb6221601)

[reddit post](https://www.reddit.com/r/CustomKeyboards/comments/jfc9f9/liberated_from_fullsize_and_and_still_shrinking/)

![iris](https://preview.redd.it/qegns2qmbbb01.jpg?width=960&crop=smart&auto=webp&s=3741cec47861e93794679667f0fa20a4fb43bf7a)

[reddit post](https://www.reddit.com/r/MechanicalKeyboards/comments/7ru844/iris_and_the_titan/)

### Plus12

Is this available retail?

![plus12](https://preview.redd.it/jyni88amyka11.png?width=960&crop=smart&auto=webp&s=8817264d1ddd8b4046c5e66755e3cf1097440747)

[reddit post](https://www.reddit.com/r/MechanicalKeyboards/comments/8zpj9u/ic_plus12_split_ergonomic_keyboard/)


### Longhorn

![longhorn](https://preview.redd.it/tpikmwi6kql51.jpg?width=960&crop=smart&auto=webp&s=b65a2fb4fbb834840d118e581198688bd1c95f1c)
[reddit post](https://www.reddit.com/r/ErgoMechKeyboards/comments/io8dzf/longhorn_kb_build_httpsgithubcomtcolarlonghorn/)

# v3.5 (2020)

Late game upset! After typing on the iris for a week I was having pain in my left thumb from keeping it in flexion above the middle thumb key. I think my only option to continue on the iris would be to rework my key mappings so that my thumb hovers on the innermost key and moves outward to hit the other ones, which would be a biggish muscle memory rework. That did not seem too desirable ergonomically. I had also been thinking about tracing the outline and making a full-hand case for it with my woodworking router, and I realized I was just basically trying to modify this iris so that it was like my ergodox. But the new QMK experience I gained gave me some good tools and a fresh perspective. I wanted to fix my errant touch typing on the pinky top row. I hadn't realized, but I have been typing the top row pinkie keys with my ring finger by reaching sideways, which I think the greater column stagger on the model 01 vs the ergodox might remedy. So I decided to pull my keyboardio model 01 out of the closet and over a 4-day weekend get my keymaps updated and spent some time typing and trying to fix those touch-typing habits. Sadly most typing programs don't use apostrophes much so I may need to find some more specialized drills to do.

So back to the keyboardio model 01 again, but this time running custom QMK firmware instead of kaleidoscope/chrysalis.

# v5 Tractyl (nah)

I was originally thinking of doing this but once I started prototyping the squeezebox I decided to focus on that instead.

I want to build something like this vertical dactyl manuform. The maker has extensive notes etc, but does indicate this is several months worth of weekends to tackle.

![tractyl](https://preview.redd.it/1k2lzwhqzqz51.jpg?width=1080&crop=smart&auto=webp&s=3feff33cddc8cacac8b4639859e10f0968631939)

[reddit post](https://www.reddit.com/r/ErgoMechKeyboards/comments/jvofrz/rebuild_finally_complete/?utm_source=share&utm_medium=web2x&context=3)

# v5 Squeezebox DIY custom

I'm currently prototyping a split vertical keyboard and the results are promising enough that I'm expecting to be able to have a working version in winter of 2021. I'm so excited about it that I'm waffling between sharing details publicly during development vs keeping quiet until I have something working and proven as a daily driver.

# v9000

At some point I want a split vertical keyboard custom built with small and tightly packed keys. Each thumb will get a track ball (or maybe directional pad, or maybe a track point) and a semicircle of small keys. All the layers will be ambidextrous and symmetric. All the layer switching will be truly independent across the hands.
