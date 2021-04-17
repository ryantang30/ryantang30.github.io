---
name: 3D Printing Toxel (Pokemon)
tools: [3D Printing, Reverse Engineering]
image: ..\assets\project_assets\toxel.jpg
description: De-complied Pokemon Sword & Shield to obtain 3D model of a Pokemon just to 3D print it out. &#35;effortmax
---

# 3D Printing Toxel (Pokemon)
*December 2019*

![3D Model of Toxel](/assets/project_assets/toxel.jpg "Philadelphia's Magic Gardens")


## Problem I was trying to solve
I wanted to get a friend interested in 3D printing so I offered to print any model he could think of, hoping that I would be able to find it on Thingiverse. Turns out, he chose an obscure Pokemon that was only just released in the new Pokemon Sword/Shield a month ago which means obtaining the model is not going to be easy.

## How I solved it
After scowling the Internet for a 3D model of Toxel, I came across a Redditor who made one just for fun and post it [here](https://www.reddit.com/r/PokemonSwordAndShield/comments/e2g12i/i_made_a_3d_model_of_my_fav_pokemon_of_this_gen/?utm_source=share&utm_medium=web2x&context=3). I reached out to the poster but did not get a reply, so eventually as I searched further for the answer to this problem and stumbled upon a forum where people were sharing on how to decompile Pokemon Sword and Shield to obtain the game assets.

This got my curiosity peaked as I always wanted to learn more about reverse engineering ever since I was introduced to in back when I was into [CTFs (Capture The Flag)](https://dev.to/atan/what-is-ctf-and-how-to-get-started-3f04) competitions.

Using this forum post as a reference and Googling away the other issues I faced, I managed to decompile the game and gained access to the 3D models of the game files, including all **898 Pokemon 3D models**, even those which are not even obtainable in-game at that time, full featured with the ability for me to adjust their body parts to any position (which is how I managed to put Toxel into a sitting position).

Eventually I extracted the Toxel 3D model, place it in a sitting position, exported as an STL file, throw it in Cura for slicing, and printed in on my Ender 3. I made a video of the process and posted on our company's Instagram to explain the process of 3D Printing. If you are interested you can find it [here](https://www.instagram.com/s/aGlnaGxpZ2h0OjE3ODY3NjE4Mjk2NTc3Mjg0?story_media_id=2207976696153677177_8233728761&igshid=1u85fp3qudvi7).

Posted this as I just thought that it was quite funny and interesting that just the need to find a single 3D model of a Pokemon led to a full fledge hours long effort to decompile a game.



_P.S Sorry for the lack of information on the forum post and guide on how to do this yourself as that information is saved in my old laptop which now has some issues booting and I am actually writing this in Apr 2021 so I can't really remember where I got the information from. I will update this post in the future again if there is interest and I can revive my old laptop's hard disk._
