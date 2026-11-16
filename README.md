# Restore-Odyssey-Stars
Reshade preset to somewhat neutralize the stupid Elite Dangerous Odyssey stellar color filter mask

Before Odyssey, planetary surfaces had lighting determined more from the host star. 
With ground FPS content added with Odyssey, Frontier added a stellar lighting mask similar to the stupid "Netflix" lighting in modern shows. 
Essentially a flat white light so that FPS settlements aren't too dark, or have too many unintended color effects from the host star. 

This repo and associated preset file spare you having to gnaw your arm off watching a Youtube video explaining each setting over the course of 20 minutes. 
Much like hitting "print" on a recipe site so you get the recipe without having to read a five page story about how meemaw inspired the recipe, blah, blah, blah. 

---------------------------------------

Installation: 

-    Download and install standard version of reshade (without full addon support) https://reshade.me/

-   Copy the preset file from this repo to the following directory:
  (your Elite installation directory/Products/elite-dangerous-odyssey-64/EliteDangerous64.exe)

- Start reshade installer

-   When the Reshade installer prompts to browse for the game navigate to: 
(your Elite installation directory/Products/elite-dangerous-odyssey-64/EliteDangerous64.exe)

- You can select the preset from this repo in the installer, and select the option to install shaders from the preset, otherwise ensure the following shaders are installed (along with default shaders):
     * Color effects by prod80 (double click and make sure all shaders in this collection are checked)

- Based on personal preferences, monitor settings, game settings, or other shader mods like EDHM you may want to adjust the settings. By default, this preset is sort of pseudo-HDR and might be a tad oversaturated for some. 
  You can access the reshade menu by default with the home key - though you might need to remap this so as not to interfere with default Elite Dangerous key bindings
    * PD80_04_Constrast_Brightness_Saturation
    * Curves
 
**Note:** Curves contrast value can vary wildly in effectiveness depending on monitor or other shader settings. 
  Best results are -1.000000 to -0.500000 Start with -0.500000 and work down towards -1.000000 and see what works best for your setup
- Contrast: -0.500000

You may also find EDFX useful: https://edcodex.info/?m=tools&entry=58

**References:**

- https://www.reddit.com/r/eliteexplorers/comments/1vcyd4t/this_is_how_i_finally_managed_to_save_the_stars/
- https://www.reddit.com/r/eliteexplorers/comments/1vc310q/sometimes_the_journey_is_the_destination/
- https://www.reddit.com/r/EliteDangerous/comments/1ve4980/finally_found_a_way_to_fix_the_stars_in_oddy_and/

 If you are an explorer who prefers deep space over the bubble, feel free to visit the IGAU discord at: https://discord.gg/vs5XngMNSS
 ALL peaceful and like-minded explorers are welcome to join IGAU.  

 More info: 
 - https://intergalactic-astronomical-union.github.io/
 - https://inara.cz/elite/squadron/6483/
 - https://edastro.com/galmap/?IGAU
