# ublock-filters

Hi everyone! In this repo I am keeping custom filter lists for ublock origin/adblock plus. So far it only contains my distraction free youtube filter.

* [Distraction free youtube](https://raw.githubusercontent.com/trevor87/ublock-filters/master/trevor-youtube.txt)
  This filter gets rid of suggestions and comments on youtube and therefore prevents getting stuck on youtube. For it to work best, also turn off autoplay before activating ublock origin on youtube. Tested on firefox mobile + desktop. Please let me know if you have improvements!

How to use:
1. So far only tested with firefox, should work with chrome as well though.
2. If you have not done so, install the [ublock origin addon](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/)
3. Open the ublock origin settings by left clicking on the new ublock icon on the top right of firefox and then pressing the settings button (on hover it says "open the dashboard").
4. Go to the "Filter lists" tab
5. Scroll down to "Custom" and check "Import"
6. Add the filter address into the field (here https://raw.githubusercontent.com/trevor87/ublock-filters/master/trevor-youtube.txt)
7. Press "Apply changes", which should have appeared in the top right corner.
8. It should work now if you reload youtube.
9. In case you want to disable the filters temporarily, this works best by pressing the ublock icon and then click on the crossed out eye-symbol (on hover it says: "click to disable cosmetic filtering on this site"). To re-enable, just do the same.
10. For maximal effectivity also disable autoplay on youtube. For this you have to temporarily turn off ublock origin, disable autoplay and turn it on again.
11. If this blocks too much for you, feel free to adjust the filter as needed. This can be done by adding the rules from my textfiles manually in the tab "My filters"

Enjoy!

PS: This is just a project for fun so it might not work in every case. If something goes wrong, please file a bug and maybe I can help!
