Adding Stardate, Local Date and Time to your Nova Theme
=======================================================
Developer: Dustin Lennon<br />
Email: <demonicpagan@gmail.com>

This application is developed under the licenses of Nova and CodeIgniter.

Install Instructions
--------------------
The following MOD will alter your Nova installation to place stardate, local time, and local date to your theme.
To install this application you need to perform the following steps.

1. Upload application/config/hooks.php to your application/config folder of your Nova install replacing 
the existing one if you haven't already modified this file. If you already have changes in this file, it's best 
that you just take the contents of this file and add it into your existing hooks.php file.

2. Upload application/hooks/UCIP-Stardate-Hook.php to your application/hooks folder of your Nova install.

3. In any theme you want to add this MOD to add `<?php echo $stardate;?>` to where ever you want this to be displayed.
Display alterations will need to be made in the file you uploaded in step 2.

At a later date and time, I MAY make this an option in the site settings to turn on/off.

Changelog - Dates are in Epoch time
-----------------------------------
1272515242: Created a more readable README for GitHub.

1271958859: As per a suggestion by Anodyne Productions on GitHub, I have made the theme alteration a hook using
CodeIgniter's hook system.

1271798383: Wrote this README to tell you how to put a stardate, local server time and date in your theme.