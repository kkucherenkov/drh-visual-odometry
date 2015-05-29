# drh-visual-odometry
Automatically exported from code.google.com/p/drh-visual-odometry

For a while now I have been looking for ways to use (computer) vision to get odometry information. This is by no means a new concept. Here are some examples (by no means a comprehensive list):

NASA used visual odometry on Mars: Two Years of Visual Odometry on the Mars Exploration Rovers (pdf)
Optical computer mice employ it and optical mouse sensors have been used in robotics; e.g. Outdoor Downward-facing Optical Flow Odometry with Commodity Sensors (pdf)
Insects leverage it. E.g., see the references in Robust Models for Optic Flow Coding in Natural Scenes Inspired by Insect Biology (pdf)
However, these solutions typically require complex and expensive setups. A little more than a month ago I stumbled over a paper by Jason Campbell, Rahul Sukthankar, Illah Nourbakhsh, and Aroon Pahwa explaining how a single regular web cam can be used to achieve robust visual odometry: A Robust Visual Odometry and Precipice Detection
System Using Consumer-grade Monocular Vision (pdf). Naturally this got me hooked. To make sure that I fully understand the presented algorithm I reimplemented it in C# and paired it with a fairly comprehensive WinForm based UI. Here is a screen shot of the result:
![Screenshop](http://www.hessmer.org/blog/wp-content/uploads/2010/08/VisualOdometryScreenshot.png)
