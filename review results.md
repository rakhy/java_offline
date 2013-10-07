Comments:
Hi, thanks for your submission.  We found some issues which need addressing:

1) Your app opens some external links in the same window. As the window is chromeless there is no back/forward navigation as well as no hardware back button on FirefoxOS devices. This dead end requires the user to restart the app. Common occurrences for external links are advertisements and sharing buttons.  External links need be declared to open in a new window by adding the attribute target=”_blank”. If you can’t change all external links this JavaScript snippet can also automate this process during runtime: http://git.io/rZ8PwA

2) To ensure that your icon shines on Firefox OS devices, we recommend you include a 60px icon that follows the Firefox OS icon guidelines (including negative space around the icon shape): http://www.mozilla.org/en-US/styleguide/products/firefox-os/icons/

3) Please make so that the images fit with phone display. Now the images are too big for display and user will be forced to slide in right side to view the full image.

Once you've made the change please resubmit your app so we can take another look.

Tested on Geeksphone Keon








help me for solve these problems.
please change the code as you want and send me a pull request.thank you.
