<div align="center">

  ![Screenshot of Firefox with the userChrome.css applied](https://github-production-user-asset-6210df.s3.amazonaws.com/115036828/302109182-156f7873-45f2-412f-9599-6a5b307df8d7.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240204%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240204T141537Z&X-Amz-Expires=300&X-Amz-Signature=df7960a936006d55b1abc07d06efde60f4d66a481c4fe880b359eb74267433c1&X-Amz-SignedHeaders=host&actor_id=115036828&key_id=0&repo_id=609767977)
  
</div>

# userChrome.css

A Firefox stylesheet meant to be minimalistic while still being usable with the mouse. Look, I love my keyboard shortcuts as much as anyone else, but sometimes it's more convenient to use the browser with the mouse.

This theme has only been tested on my specific setup and there is no guarantee it will work anywhere else. Regardless, if you try it and run into any issues, feel free to open an issue or a pull request.

## Installation

Enable the option `toolkit.legacyUserProfileCustomizations.stylesheets` from your `about:config` or `user.js` file. Then open your profile folder (you can find the location in `about:profiles`), create the folder `chrome` inside of it, and place the `userChrome.css` file inside.

Any theme and density should work, but the theme is meant to be used with Firefox's default Dark theme (not the System theme) and Compact density (enabled with the option `browser.compactmode.show` in `about:config`).

If you want to watch a video explaining the installation process, [watch my video here](https://www.youtube.com/watch?v=0QVs1jVuA8c).

## Startmenu

You can find the startmenu used in this screenshot at [firefox plugin store](https://addons.mozilla.org/en-US/firefox/addon/bonjourr-startpage/)

The Bonjourr theme can be found in my [customization-tooling](https://github.com/POP303U/customization-tooling) repo. 

## Credits
Based off [FirefoxCSS-Darknight](https://github.com/BriLHR/FirefoxCSS-Darknight) and [keyfox](https://github.com/AlfarexGuy2019/keyfox/), with additional lines from [Cascade](https://github.com/andreasgrafen/cascade).
