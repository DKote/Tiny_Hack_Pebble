Tiny Hack
================

<b> The hacked files for Tiny Bird on the pebble <b/>

================

<b> <l> I Am Not Responsible for anything that heppenes to your watch or your score <l/> <b/>

================
<b>Tiny Hack Manual Guide </b>
================
Tiny Hack Gets ride of Hight Limitation, Pipe Collision is disabled, and you start with 99 points.
If you would like to change the stuff on your own here is the codes

<br>Line 79 Start with score 99 <code>Score = "99"</code>
<br>Line 148 Fly as high as you want <code> if(y >= 999) </code>
<br>Line 185 No pipe Collision
<code> //if(!collision) {
  <br>   //collision = collision_occured();
  <br> if(collision) {
      <br> vibes_short_pulse();
  <br> }
</code>

Tiny Hack Auto Install Guide
===============
<br><b>DownLoad PBW <a href="http://builds.cloudpebble.net/4/0/40cd8543-f96e-4c37-858e-67ccc0d86232/watchface.pbw">Here</a> </b>
<br>Includes Pokemon RED HEAD bird,
<br>Title Tiny Hack,
<br>Score Start "999999999"


Errors
===============
