Graphycs Sanity Test
System: OS X El Capitan 10.11.6
GPU: Intel Iris Pro 5200
Soft: Desktop Firefox Nightly
Project: Browser
Ver.: 51.0a1 (2016-08-05)
Type: Manual test
Spec.: Discover bugs and quality issues related to specific graphics chipsets
# |        Title               |    steps         |  Expected result      |  Actual Result     |  Pass/Fail
--|----------------------------|------------------|-----------------------|--------------------|-----------------
1 | Start Firefox browser      | click on icon    | browser started       | open start tab     |       P

2 | Resize to 1024x768         | firebug resize   | adaptive disp after   | adaptive disp aft  |       P

3 | Load nytimes.com & scroll  | scroll up & down | adaptive scrolling    | adaptive scrolling |       P

4 | Open & explore at new tab  |scrolling&skipping|all pics scroll normal | up&down scroll norm|       F
  |page pinterest.com          |images on page    |                       | 1. don't work fast img 
  |                            |                  |                       |skipping bcz img loaded
  |                            |                  |                       |with delay 2. Don't save "cookies"

5 | Quickly switching between  | Fast cliking on  | pages disp. norm.     | pages disp. norm.  |       P
  | the two open tabs          |two different tabs|

6 | play high definition videos|open & play a few | will be work normal   | 360 video has playing |    F
  |from youtube.com in fist tab|videos in HD, full HD                      with strong lags (+/- 10 sec.)
                                and 360 video                              video player has long delay
                                                                           after clik on all buttons
7 | Load cnn.com in the second |type cnn.com in 2th| page open and scroll | page was been redirected|  P
  |tab and scroll page          tab & scroll around  normal                to edition.cnn.com, scroll 
                                                                           normal
8 | Play video at cnn.com      |find video & click| will play normal      | played normal           |  P
                                play