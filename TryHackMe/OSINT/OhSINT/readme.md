## TryHackMe Room: OHSINT https://tryhackme.com/room/ohsint

**Step 1: Downloaded the Image**

Simple start. Just downloaded the image that was provided in the room.

 ---
 
**Step 2: Tried Reverse Image Search**

Used TinEye to analyze the image.
Result? Didn’t find anything. No matches or useful leads.

---

**Step 3: Used FotoForensics**

Uploaded the image to FotoForensics
Checked for any hidden data, layer manipulations, or clues.
Again, nothing helpful showed up.

---

**Step 4: Used ExifTool**

Here’s what I did:
1.	Downloaded ExifTool.
2.	Ran the command to analyze metadata:
Found something interesting!
In the metadata, this appeared:
Copyright: OWoodflint

 ---

**Step 5: Investigated the Name**

Searched OWoodflint on Google.
Checked out associated social media profiles and eventually got a BSSID — this was the key to the location data.
 
---

**Step 6: Used Wigle.net**

Used Wigle.net to search the BSSID.
At first, it pointed to San Francisco.

 ---

**Step 7: Hmm... Inconsistent Info**

Kept looking because things weren’t adding up:
•	Saw references to New York on a blog site.
•	Then hints started showing UK.
•	Again, another UK clue.
•	Finally, after checking further, found the correct city: London.
 
 --- 

**Step 8: Found the Password**

Opened the view source of the WordPress blog post.
Searched carefully and found the password hidden in there.
Was a bit quirky, but yep — that’s where it was hiding.

 ---

**Step 9: The holiday city**

Quite easy. Checked the wordpress blog post I got from github and the holiday place was revealed.

 ---

**Final Thoughts**
Loved this room! A good mix of tools and creative digging.
Biggest lesson: Don't stop at the first result — follow the trail and layer it all together.
Sometimes the info is just one layer beneath what’s visible.




