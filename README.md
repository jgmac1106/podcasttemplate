Podcast Page Template
=================

This is my attempt to create a page for a podcast show. You could create a file for each podcast on your own site but this site assumes you create a new post for each episode somewhere.

Adding Episodes
------------

This page is set using CSS Grid. Each show is set up as a "podbox" There is a featured episode in podbox d.To add another episode you will edit this podbox but before you do that let's make another episode.

First copy "podbox A" from lines 73-84.Then change all the information in the box with that which is the featured show "podbox h"

Now update your "podbox h" with your latest show.

Next change "podbox a" to "podbox a" until you get to the last show and add a new letter.

Now you need to add the CSS. Go to the css/podcast.css file. Gow to the last letter. The shows are arranges in threes columns, either 4/ span 2, 6/ span 2, or 8/ span 2.

If your next letter would be 6/ span 2, or 8/ span 2 leave the row alone. If you are adding 4/ span 2 you must move the grid-row: row #; up one

Then do the media query for small screens. Every podbox letter will be in @media (max-width: 800px) just copy and paste the last letter. Change it to your new podbox letter and increase the grid-row by one.

h-feed
------------
The html of the podcast already contains the correct microformats for an h-feed. Just make sure not to style any classes starting with p-, u-, or h-.

RSS
------------
There is also an xml file included with the proper data needed for Itunes but any feed reader can pick it up.

-------------------

\ ゜o゜)ノ
