**Hands-On Test**

**Select one of the games below (all of them can be played in demo mode):**

- [ ] Big bass float my boat  
- [ ] Esqueleto explosivo 2  
- [x] Bling Bling Penguin  
- [ ] Unusual suspect  
- [ ] Sky Bounty

**Test the game  \- Bling Bling Penguin:**  
**Check list of tests finished:** 

**○ Functional Test:**

- [x] ~~Check if the game loads correctly on different browsers (Chrome, Firefox, Safari, Edge)~~

- [x] ~~Ensure that all buttons and controls (such as spin, bet, autoplay) work as expected.~~

- [x] ~~Test the game with different bet values and check if the winnings are calculated correctly.~~

- [x] ~~Check if the bonus features (if any) are activated and function correctly.~~

- [x] ~~Confirm if the animations and graphics are displayed without issues.~~

**Usability Test:**

- [x] ~~Evaluate the game's user interface for ease of use.~~

- [x] ~~Test the game's responsiveness on different screen sizes (desktop, tablet, mobile).~~

**Performance Test:**

- [x] ~~Monitor the game’s performance (e.g., loading times, frame rates) under normal conditions and heavy loads~~  
      

**Report the Results:**

○ Create a detailed bug report for any issues found, including:

* Steps to reproduce the bug  
* Expected result  
* Actual result  
* Severity level (e.g., minor, major, critical)

○ Include screenshots or videos, if necessary, to illustrate the issues.

**Submit the Report:**

* Compile your findings into a document or bug-tracking tool (e.g., JIRA).  
* Submit the report along with any additional observations or improvement suggestions.

**5\. General Overview**

**○ Even though this is not a question, we’d like to hear why you selected this game.**  
Besides being the game from the company, which I thought was most suitable for providing a complete feedback, I was impressed when I opened the game. The music is engaging and very well structured for each bonus and in the base game. It changes and provides great sound feedback, it's extremely responsive, has a great rhythm, and the lyrics fit with every moment of the game.

**○ What are the ups and downs?**  
As mentioned above, the music is extremely engaging and good, the bonuses are fun and interactive, and the Penguin is charismatic. However, on the negative side, several assets have poor quality on some devices. On Mozilla, the game is quite laggy, which made me play less because it hindered my understanding of what was happening in the game. Some animations clearly have chopped frames, like the coins that move toward the wheel.

**○ What would you consider a factor that would make you play again?**  
The music and sound effects are extremely responsive, have a good rhythm, are very engaging, and the bonuses are fun and interactive. They set a good expectation. I played for a good few minutes without checking for bugs just because of the adjectives mentioned.

**○ Was this an engaging experience?**  
Yes, especially the music and SFXs. I can say I really liked the game and would recommend it to friends to play.

**Details of the bugs found:**

All the bugs mapped in this document will have evidence attached on the link below: [Mapped Evidence - Ino Games Test](https://drive.google.com/drive/folders/11buImJ1iyDa14PpM9o_cTcAxg2KcJVap?usp=drive_link)  
Note: (I created an ID system just to organize the issues).

---

**ID**: \#01  
**Priority**: Critical  
**Browser and Device Used**: All Devices and Browsers  
**Version and Environment Tested**: Slot Catalog Demo Version  
**Description**: When playing a round, the error message "511 \- Out of sequence event." appears and freezes the game.  
**Evidence:** [Error 511](https://drive.google.com/file/d/1x2fqd08BR72HA2vz47q0M1dd5Oui7pzB/view?usp=drive_link)

**Steps to Reproduce**:

1. Open the game;  
2. In the middle of a Bonus round, reload the page (F5);  
3. The game freezes with the mentioned message displayed on the screen, and only clearing the cache restores the game to normal.

**Expected Result**: The game should refresh normally, the message should not appear, and the game should not freeze.  
**Issue Classification**: Bug.

---
 
**ID**: \#02  
**Priority**: High  
**Browser and Device Used**: Mobile \- All browsers  
**Version and Environment Tested**: Slot Catalog Demo Version  
**Description**: Game information overlapping message after Big Win roll-up  
**Evidence:** [Informartion under information](https://drive.google.com/file/d/1f-CmK7oF02tS9OjxzliEWbC9gMcOXmdI/view?usp=drive_link)

**Steps to Reproduce**:

1. Open the game;  
2. Play a bonus round and get a Big Win;  
3. Open the Paytable during the Big Win;  
4. Close the Paytable screen;  
5. Check that the Total Won information is overlapping the "Select" message.

**Expected Result**: The Total Won field should not overlap the Skip message.  
**Issue Classification**: Bug

---

**ID:** \#03  
**Priority:** High  
**Browser and Device Used:** PC \- All browsers  
**Version and Environment Tested:** Slot Catalog Free Demo Version  
**Description:** It is possible to scroll the change bet without the mouse holding the game screen  
**Evidence:** [Scroll change bet without mouse select](https://drive.google.com/file/d/1W6FKgUKzvCYBMJvnMYYBWiR6ngYZpyST/view?usp=drive_link)

**Steps to Reproduce:**

1. Open the game;  
2. Open the screen to change the bet;  
3. Click on the screen, drag the mouse outside the game, and release it;  
4. Move the mouse back to the change bet screen;  
5. Check that the scrolling motion still occurs without the mouse selecting anything.

**Expected Result:** The scrolling function should only work when the mouse is selecting the screen.  
**Issue Classification:** Bug

---

**ID**: \#04  
**Priority**: High  
**Browser and Device Used**: Mobile \- Chrome \- Portrait Orientation  
**Version and Environment Tested**: Slot Catalog Free Demo Version  
**Description**: The Button Bar interface is cut off in Chrome Mobile  
**Evidence:** [Button Bar Interface under the grid](https://drive.google.com/file/d/1Ou46MO0QUqUil95MxdadCAXJferh8LQX/view?usp=drive_link)


**Steps to Reproduce**:

1. Open the game on a mobile device in portrait orientation;  
2. Check that the Button Bar interface is cut off.

**Expected Result**: The interface should not be cut off to prevent issues for the user.  
**Issue Classification**: Bug

---

**ID**: \#05  
**Priority**: High  
**Browser and Device Used**: All Devices and all Browsers  
**Version and Environment Tested**: Slot Catalog Free Demo Version  
**Description**: The Lobby button is not working in any game state  
**Evidence:** [Lobby Button](https://drive.google.com/file/d/1er4xk3upqVcZJZQl1tZl1QdqYaAQ_LFx/view?usp=drive_link)


**Steps to Reproduce**:

1. Open the game;  
2. Open the Menu;  
3. Go to the Lobby option;  
4. Press the Lobby button;  
5. Check that the button does not work.

**Expected Result**: The button should function correctly.  
**Issue Classification**: Bug

---

**ID**: \#06  
**Priority**: High  
**Browser and Device Used**: PC \- All Browsers  
**Version and Environment Tested**: Slot Catalog Free Demo Version  
**Description**: It is possible to play any bonus with the Menu open  
**Evidence:** [Play bonus without click](https://drive.google.com/file/d/1jLLixKSbBZOXkzp8RnrTKN4ro2baVEAN/view?usp=drive_link)


**Steps to Reproduce**:

1. Open the game;  
2. Trigger a Bonus;  
3. On the screen with the message "Select anywhere on the screen," open the Menu;  
4. Open the game's settings tab;  
5. Select the speed button, which will be disabled;  
6. Check that the game starts with the Menu open.

**Expected Result**: The bonus should not start with the Menu screen open.  
**Issue Classification**: Bug

---

**ID**: \#07  
**Priority**: High  
**Browser and Device Used**: Mobile \- All Browsers  
**Version and Environment Tested**: Slot Catalog Free Demo Version  
**Description**: The message "Select anywhere on the screen" does not appear on Mobile due to screen resolution.  
**Evidence:** [Can't see the message to start bonus](https://drive.google.com/file/d/1hdaAImDgLil002iWqjA56IafbplZt757/view?usp=drive_link)


**Steps to Reproduce**:

1. Open the game on Mobile;  
2. Trigger a Bonus;  
3. On the screen with the message "Select anywhere on the screen," check that the message does not appear.

**Expected Result**: If possible, adjust the resolution so the message appears.  
**Issue Classification**: Bug

---

**ID**: \#08  
**Priority**: Medium  
**Browser and Device Used**: PC \- All Browsers  
**Version and Environment Tested**: Slot Catalog Free Demo Version  
**Description**: Clicking on the edge of the button does not trigger the Bling Bling Bonus Wheel  
**Evidence:** [Border of the Button on Bonus](https://drive.google.com/file/d/19cdT5DvwziUIFTAD4EqlZZ0FCInlR7aQ/view?usp=drive_link)


**Steps to Reproduce**:

1. Open the game;  
2. Trigger a Bonus;  
3. Click on the edge of the yellow button;  
4. Check that the game does not start when clicking on the yellow edge of the button.

**Expected Result**: The button should work across its entire hitbox.  
**Issue Classification**: Bug  

---

**ID**: \#09  
**Priority**: Medium  
**Browser and Device Used**: PC \- All Browsers  
**Version and Environment Tested**: Slot Catalog Free Demo Version  
**Description**: It is possible to click and drag an image from the Paytable  
**Evidence:** [Assets clickable on Paytable](https://drive.google.com/file/d/1ExaSSQ2-uRVGjbFUeLWiJibXqOEtwXVw/view?usp=drive_link)


**Steps to Reproduce**:

1. Open the game;  
2. Open the Menu;  
3. Open the Paytable;  
4. Click on an image and try to drag it;  
5. Check that it is possible to drag the image and drop it in the browser.

**Expected Result**: No image from the Paytable should be available for the user to interact with.  
**Issue Classification**: Bug

---

**D**: \#010  
**Priority**: Medium  
**Browser and Device Used**: PC \- Mozilla Firefox  
**Version and Environment Tested**: Slot Catalog Free Demo Version  
**Description**: Grid animation with artifact  
**Evidence:** [Grid animation with artifact](https://drive.google.com/file/d/1SXy0qJu89H2hdSVTKnE-dDy00wlcPynL/view?usp=drive_link)


**Steps to Reproduce**:

1. Open the game in the Mozilla Firefox browser;  
2. Play as soon as the game loads;  
3. Check that the game is frozen and there is an invisible square artifact in the middle of the game grid.

**Expected Result**: If possible, adjust the game's performance in Mozilla and remove the artifact.  
**Issue Classification**: Bug

---

**ID**: \#011  
**Priority**: Medium  
**Browser and Device Used**: PC \- All Browsers  
**Version and Environment Tested**: Slot Catalog Free Demo Version  
**Description**: It is possible to make multiple clicks on all close buttons in the game.  
**Evidence:** [Multiples clicks on button X](https://drive.google.com/file/d/1BuhO6tbZeMdB5URLsH-EBSKLr8H0vY8I/view?usp=drive_link)


**Steps to Reproduce**:

1. Open the game;  
2. Open the Menu;  
3. Select any option that contains the X button to close;  
4. Check that it is possible to click multiple times on the X button.

**Expected Result**: The button should only be clickable once.  
**Issue Classification**: Bug

---

**ID**: \#012  
**Priority**: Low  
**Browser and Device Used**: All Devices and All Browsers  
**Version and Environment Tested**: Slot Catalog Free Demo Version  
**Description**: Adjust the Quality of the Flag Asset in the Free Spin Bonus  
**Evidence:** [Quality Asset of the Flag](https://drive.google.com/file/d/1Gs4cdWrT-PQMwKT_HGgNffCn0_DNIkWO/view?usp=drive_link)


**Steps to Reproduce**:

1. Open the game;  
2. Trigger the Free Spin Bonus;  
3. Check that the Flag Asset has visible PNG cut marks and low resolution quality.

**Expected Result**: The quality of the asset should be more defined.  
**Issue Classification**: Bug

---

**ID**: \#013  
**Priority**: Low  
**Browser and Device Used**: PC \- All Browsers  
**Version and Environment Tested**: Slot Catalog Free Demo Version  
**Description**: The animation of the glow around the last prize in the Base Game is faster than the others.  
**Evidence:** [Brightness animation on border](https://drive.google.com/file/d/1Xq5kPvHkqDGkF5PoYJ-1EZAn4lR7-IFQ/view?usp=drive_link)


**Steps to Reproduce**:

1. Open the game;  
2. Check the animation of the glow around the prizes on the left, below the Character.

**Expected Result**: Adjust the animation so that it matches the others.  
**Issue Classification**: Bug

---

**ID**: \#014  
**Priority**: Low  
**Browser and Device Used**: Mobile \- All Browsers  
**Version and Environment Tested**: Slot Catalog Free Demo Version  
**Description**: The animation of the coins up to the wheel path is cut off at the end.  
**Evidence:** [Coin animation](https://drive.google.com/file/d/11FLrcD7e9e9l5xhNDRsGB2FcRajMGtPM/view?usp=drive_link)


**Steps to Reproduce**:

1. Open the game;  
2. Trigger a Bonus;  
3. Check that the animation of the coins is cut off when they reach the Wheel.

**Expected Result**: If possible, adjust the coin animation.  
**Issue Classification**: Bug

---

**ID**: \#015  
**Priority**: Low  
**Browser and Device Used**: All Devices \- All Browsers  
**Version and Environment Tested**: Slot Catalog Free Demo Version  
**Description**: The quality of the fish carousel assets in the game introduction is low.  
**Evidence:** [Quality Asset of the Fish caurosel](https://drive.google.com/file/d/1ZqWV-hSE1bDTjWHM1NituLrV55iPzfO3/view?usp=drive_link)


**Steps to Reproduce**:

1. Open the game;  
2. Check the quality of the fish carousel in the game introduction, before the base game starts.

**Expected Result**: If possible, adjust the quality of the asset.  
**Issue Classification**: Bug  

---

**ID**: \#016  
**Priority**: Low  
**Browser and Device Used**: All Devices \- All Browsers  
**Version and Environment Tested**: Slot Catalog Free Demo Version  
**Description**: It is possible to notice the reset of the water animation in the background.  
**Evidence:** [Background Water Animation Flick](https://drive.google.com/file/d/1K34_OJQZmZp-nWLBdiP-OAY8pbyJ0uK0/view?usp=drive_link)


**Steps to Reproduce**:

1. Open the game;  
2. Stay on Base game;  
3. Check the reset of the water on background.

**Expected Result**: If possible, adjust animation of water.

**Issue Classification**: Bug

---

**ID**: \#017  
**Priority**: Low  
**Browser and Device Used**: All Devices \- All Browsers  
**Version and Environment Tested**: Slot Catalog Free Demo Version  
**Description**: Replacing the word “Select” with “Click” would be more intuitive.  
**Evidence:** [Change the word "Select" to Click](https://drive.google.com/file/d/1k-hn3_HZXzYiGPqcqMgwGcLDtHZxbZ5m/view?usp=drive_link)


**Steps to Reproduce**:

1. Open the game;  
2. Trigger a Bonus;  
3. Check the message displayed to start the bonus.

**Expected Result**: If possible, it would be better to adjust this message.  
**Issue Classification**: Improvement

---

**ID**: \#018  
**Priority**: Low  
**Browser and Device Used**: All Devices \- All Browsers  
**Version and Environment Tested**: Slot Catalog Free Demo Version  
**Description**: Adding a comma and changing the period would be more intuitive after two decimal places.  
**Evidence:** [Change the point to domma after 2 decimmals place](https://drive.google.com/file/d/1MtJu1D9jEbuL1B9WQmIm2cJ_IpHmZWSH/view?usp=drive_link)

**Steps to Reproduce**:

1. Open the game;  
2. Check the quality of the fish carousel in the game presentation, before the base game.

**Expected Result**: If possible to change, make the interface mor intuitive for the users.  
**Issue Classification**: Improvement

---

**ID**: \#019  
**Priority**: Low  
**Browser and Device Used**: All Devices \- All Browsers  
**Version and Environment Tested**: Slot Catalog Free Demo Version  
**Description**: Adjust the size of the game.  
**Evidence:** [Adjust game size on MB](https://drive.google.com/file/d/1FyWLEcvT4ZQNcCtvVv0XPQqnKl1ANMyh/view?usp=drive_link)

**Steps to Reproduce**:

1. Open the game with Inspection and check the size of the game.

**Expected Result**: If possible, adjust the size of the game. Currently, it weighs 44.0MB in all browsers.  
**Issue Classification**: Improvement

