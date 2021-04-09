---
layout: post
title: 'Shut the #@&! up!'
date: 2021-04-09 14:31 +0200
img: shut_up/shut_up.png
tag: game
---
[IF YOU DON'T WANT SPOILERS GO PLAY SHUT UP BEFORE YOU READ.](https://kimcodekill.itch.io/shut-up)

Shut up is a game made for a university game jam with the theme "#@&!". We were a team of 3 developers and had no idea how to interpret the theme at first, it took the whole first evening to come up with anything. We decided to interpret the theme as censorship based on the way comics censor curse words (btw it's called [grawlixes](https://en.wiktionary.org/wiki/grawlix)). We also decided that we wanted to try making a 3D game as everything we had made so far was 2D.

![gameplay](../assets/img/shut_up/gameplay.gif)

The player acts as a government spy that has to quiet rebels using duct tape and make the allies voices louder with megaphones. Every mission has what the government considers positive messages (green) and negative messages (red). The goal is to listen to what people are talking about by reading their speech bubbles, and figure out if they should be quieted or heard. When people talk, they influence society which is shown by a bar at the top of the screen. If the positive messages influence all of society, you win! 

![winning](../assets/img/shut_up/winning.gif)

We decided to use symbols that for most people had no meaning so that we could pretend each symbol meant a single word. This made it easy for us to condense full conversations into speechbubbles without making it too confusing. The challenge in this game isnt about using information, its about finding it. The player has a slow walking speed and they must keep their eyes open and keep moving constantly to not miss conversations and end up losing.

Since we had to use so much of our time trying to figure out from scratch how to do movement and camera control in a 3D game, there are issues that interrupt the experience. The sensitivity of the camera is far too high, the volume of sounds is far too high, and there is no menu available to change this. There is also no way to exit the game unless you use the alt+F4 unity trick which is really annoying. A menu with sensitivity and volume control, as well as menu/exit buttons is the first thing i would add if i made it now. 

Apart from getting the move/look logic working, I was responsible for programming the mechanics and UI. There is a random chance every tick that an npc will start talking. It is also randomly selected to be negative or positive. Every second the npc will contribute to the current influence; 0 if taped, 1 if normal, and 2 if megaphoned. Working with so much randomness led to multiple bugs, but getting control of the randomness was very interesting and satisfying.

The mechanics themselves do what they are supposed to. It's fun to walk around and snoop on conversations, and there is pressure to not let the bar get too red. It looks basic, but thats absolutely fine according to me. It doesnt need to have a detailed environment since the player should spend most of their time looking at the characters. It does however need lots of polish and quality of life improvements.

Textures and models were made by Henrik H. and the levels were designed by Erik P. in close cooperation. 

If there is anything more you would like me to talk about, please send me an email and I'll add an addendum to this post.