# Re-Cycling Old Hotel Cards as NFC Tags



![](https://private-user-images.githubusercontent.com/160423464/347178156-4c6039ca-b045-4cd0-a5a3-781c6492c7e8.jpg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA1Njg1NjQsIm5iZiI6MTcyMDU2ODI2NCwicGF0aCI6Ii8xNjA0MjM0NjQvMzQ3MTc4MTU2LTRjNjAzOWNhLWIwNDUtNGNkMC1hNWEzLTc4MWM2NDkyYzdlOC5qcGc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNzA5JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDcwOVQyMzM3NDRaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1lMzM5YWQ4ZDhiOTgwM2NiYWYyYmRiZTQ0YTBkMjQ1N2RiN2YzODUyMjU2NThmMWFmZmJiZTAxOWYwNTVlMzcwJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.CkSQ0JkTCO6pf-3fN44hLCZlSv5NTP63LbHSCDiS6sw)

There is a little-known trick with hotel cards. By using certain android apps and an NFC capable phone, we can either completely format the card, or, if write protected, use it to run automations! Below will cover both methods.

---

## Before you Begin

* Ensure you have an NFC-CAPABLE smartphone. 

* Know that this can be time consuming (30 mins+ without your phone) 

* Make sure your hotel card does not have a black magnetic strip on the back (make sure it's NFC-based).

---

## 1. Check if the tag is write protected.

To do this:

1. Download the [**MiFare Classic Tools**](https://play.google.com/store/apps/details?id=de.syss.MifareClassicTool&hl=en_US) from the Google Play Store.

2. Run the app and tap **"Write Tag."**

3. Place your tag underneath your phone's NFC chip.

4. Tap **"Factory Format"** -> Tap **"Factory Format."**

5. Select extended-std.keys **and** std.keys -> press **"start mapping and format tag."**

**If any "write issues" occur**, select **"Write as much as possible."**

## 2. Verify that the tag is now fully writable.

To do this, 

1.     downlaod the [NFC TOOLS](https://play.google.com/store/apps/details?id=com.wakdev.wdnfc&hl=en_US&pli=1) app by wakdev

2.    go to the "write" section

3.    add a record

4.    text

5.     type "1234" and tap "OK"

6.    write / 11 bytes

After you press "write" approch your NFC hotel card with your phone. If it writes, you now have a blank NFC tag that you can do anything with! hooray! 

**If there is a "Write error," continue reading.**

## 3. Bypassing write errors.

If there is a write error, fear not! Below is a way to use the card for a plethora of automations instead.

1. Downlaod [NFC ReTag](https://play.google.com/store/apps/details?id=com.widgapp.NFC_ReTAG_FREE&hl=en_US) from the Google Play Store. 

2. Tap your phone against the NFC card -> tap "Add TAG"

3. Name your tag whatever you want.

4. Press the **green "+Activity"** button on the botttom of the screen.

5. Choose any automation from the menus.

6. Configure your automation and press "OK."

Now, tap your phone against the NFC tag. **If prompted, tap "Open with NFC-ReTag"**

**Enjoy!**
