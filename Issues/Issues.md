# PC Issues & Solutions Log

## Issue Log Format
Each issue is documented with:
- Description of the problem
- Troubleshooting steps taken
- Final solution
- Additional context when relevant

---

## Audio Cutting Out During Gaming
**The Issue:**
Random audio dropouts during gaming sessions, lasting 1-2 seconds. No error messages in Windows, just sudden silence followed by audio resuming.

**Troubleshooting:**
Discovered the issue occurred when CPU hit high usage. Audio dropouts coincided with CPU spikes in monitoring software..

**Solution:**
RAM/FCLK issue, make sure timings are not too tight and be weary that temperatures rise the longer you game. I was going into instability. Fix was increasing the TRFC from 500 too 560

---

## Marvel Rivals randomly Crashing
**The Issue:**
Marvel would run fine until it wouldnt and hard crash, would force verification of files, refused to re-open sometimes

**Troubleshooting:**
Used OCCT tool to troubleshoot performance on the PC and found that when stress testing my FCLK/DRAM I would crash/bluescreen, this lined up with the heavy usage from Marvel Rivals. 

**Solution:**
Tuned FCLK from 2133 to 2067 and DRAM from 6400 to 6200 and the FCLK instability that was causing the game crash was resolved.

---

[Continue this format for each new issue]
