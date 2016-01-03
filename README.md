# FRC Software Releases
A big list of all the FRC team software releases from recent years!

Quotes are not necessarily verbatim.

# 2015 season code

## Team 174: Arctic Warriors

> * Java simulator - Unobtrusive "simulator" that can be used with any teams java code. It sounds like we took a similar approach to what team 254 did
> * Custom SmartDashboard widgets - Custom widgets to show robot state, motion profiling state, and our autonomous editor
> * Autonomous Scripting - Command based autonomous scripts. Stored as text files on the robot, can be edited from the SmartDashboard
> * Motion Profiling - I had my students hand roll a simple version for straight paths. We also took team 254's spline library as is.

> In developing our software this year, we tried to have a more structured design process. We made a design notebook for our entire robot which will be released at a later date, including class diagrams and sequence diagram. We used the Agile methodology to develop our software, which worked quite well with the structure of a FIRST season and our constantly changing requirements

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=137819) | [Robot Code on GitHub] (https://github.com/ArcticWarriors/snobot2015) | [PDF](https://github.com/ArcticWarriors/snobot2015/raw/master/Team174Software.pdf)

## Team 254: The Cheesy Poofs

> This year’s software includes new features such as a test harness and simulator code to run the program on a computer, web-based graphing tools, constants editor, and autonomous selection, blocking autonomous routines, and a controller that calculates and follows a trapezoidal motion profile, on the fly.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=137843) | [Robot Code on GitHub](https://github.com/Team254/FRC-2015) | [Simulated robot hardware on GitHub](https://github.com/Team254/Sim-FRC-2015) | [Simulator on GitHub](https://github.com/tombot/FakeWPILib) | [GitHub](https://github.com/Team254)

## Team 624: CRyptonite

>  This includes a library for using CAN Talons in LabVIEW with limited memory overhead, a scripted autonomous structure and text editor with a customizable programming language, and our version of Smart Dashboard which uses UDP instead of Network Tables. It also contains our offseason RGB lights code.

>  We experimented with Feed Forward and Motion Profiling in the fall. With some tuning, I was able to get our 2015 bot and a kitbot to go any distance I wanted without encoders (within an inch or two). I am still working on the integration with Feedback to make it more accurate and the latest code will be available on Github. This project may not be able to be opened until Kickoff because older versions of LabVIEW do not support projects built under Beta.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=140790) | [Robot Code on team website](http://team624.org/files/624%202015%20Code%20Release.zip) | [Robot Code from Beta 2015](http://team624.org/files/624-Feed-Forward-R-D.zip) | [Team Website](http://team624.org/?controller=page&action=programmingResources) | [GitHub](https://github.com/Team624)

## Team 971: Spartan Robotics

> * Most of the stuff we modify year-to-year is written in C++ and Python
> * We use Python to design our controllers and generate raw matrices for our state feedback controllers that can be used with the C++ code directly. [Another thread diving into our control system code and theory is available here](http://www.chiefdelphi.com/forums/showthread.php?t=129574)
> * We recently switched from an older build system based mainly on GYP files to Bazel, which is the publicly-available version of Google's build system
> * All robots included in this snapshot (2014 competition robot (Mammoth), 2014 3rd robot (Butterknife), 2015 competition robot (Subzero), and 2015 third robot (Robonauts?)) are up-to-date for the RoboRIO and other 2015 FIRST control system components

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=140568) | [Robot Code on team website](http://robotics.mvla.net/spartanrobotics/releases/src/2015_code.tar.gz) | [General software info on team website](http://frc971.org/content/2015-software) | [CAD on Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?threadid=137883) | [Team Website](http://frc971.org/)

## Team 1540: The Flaming Chickens

>  We ran our robot software department on a code-review setup: everything got developed in a separate branch, pull-requested, and code-reviewed before merge. ]You can see the log of this on the project page.](https://github.com/flamingchickens1540/quasar-helios-2015/pulls?q=is%3Apr+is%3Aclosed) 107 pull requests!
> This ended up working really well for us - it allowed us to edit each other's code to be higher quality in a way that gave everyone rapid feedback and allowed team members to become much better programmers over the course of the season.
>
> (Also, for reference, our code uses [the Common Chicken Runtime Engine](http://www.chiefdelphi.com/forums/showthread.php?t=130813), our dataflow-based robot code framework, which should explain some of the nonstandard coding.)
> 
> One other thing that helped: multi-layered autonomous modes. Some of our modes would pick up totes. To do this, they would start the pseudo-autonomous mode for autoloading (which was also used by the drivers), which would, in turn, also start the pseudo-autonomous mode for automatically controlling the elevator stacking sequence (also available to the drivers separately.)

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=137255) | [Robot Code on GitHub](https://github.com/flamingchickens1540/quasar-helios-2015) | [GitHub](https://github.com/flamingchickens1540)

## Team 1701: RoboCubs

> This year we used the new AndyMark Swerve Drives.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=137028) | [Robot Code on GitHub](https://github.com/bh202548/Robocubs-Code-2015/)

## Team 1939: Kuhnigits

> This year was exciting for the programming team. New control techniques such as PID were explored, and new Talon SRX speed controllers made programming and wiring easier. Our team believes heavily in the WPILib programming model of Subsystems and Commands. All of our code follows this Command Based model.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=139606) | [Robot Code on GitHub](https://github.com/FIRST1939/RecycleRush2015)

## Team 2122: Team Tators

> As one of our seniors put it, "Wow this is some cool code for you!" I couldn't have put it more eloquently.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=137296) | [Robot Code on GitHub](https://github.com/Team2122/Kartoshka)

## Team 2363: Triple Helix

> This was definitely our most complex robot to date. Comments and questions welcome.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=137180) | [Robot Code on GitHub](https://github.com/TripleHelixProgramming/recycle-rush/tree/working_branch) | [GitHub](https://github.com/TripleHelixProgramming)

## Team 2485: WARLords

> Our Sequencer Factory class enabled us to rapidly create and modify auto sequences, which could also be used in teleop.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=136899) | [Robot Code on GitHub](https://github.com/team2485/frc-2015)

## Team 3081: Kennedy RoboEagles

> There are several good examples of combining state machines with the Command-Based Robot framework.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=140791) | [Robot Code on GitHub](https://github.com/KennedyRoboEagles/PublicRobotCode)

## Team 3467: The Windham Windup

[Robot Code on GitHub](https://github.com/WHS-FRC-3467/Skip-5.5) | [GitHub](https://github.com/whs-frc-3467)

## Team 3620: The Average Joes

> Most of the code is pretty typical FRC code (complete with warts). There are a few unusual things in there, though, that other teams may find useful:
> 
> * event logging.
> * data logging.
> * UDP transmission of JSON encoded data to an onboard co-processor.
> * UDP reception of JSON encoded data from an onboard co-processor.
> * adding third party jars to the build.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=140729) | [Robot Code on GitHub](https://github.com/FRC3620/FRC3620_2015_AverageJava) | [White paper](http://www.chiefdelphi.com/media/papers/3189)

## Team 4561: TerrorBytes

> Our robot has a mecanum drive train, an elevator, a telescoping arm, and a pneumatic claw. This is its code.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=138078)
[Robot Code on GitHub](https://github.com/Terrorbytes/TB2015)
