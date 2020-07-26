---
layout: post
title: Robot Tugboat
subtitle: An autonomous mini-tugboat
image: /img/projects/tugboat/square.jpg
share-img: /img/projects/tugboat/square.jpg
tags: [Fundamentals-Of-Robotics]
---

This project involved modifying a prebuilt tugboat and adding sensors, sensor mounts, Arduinos, and other hardware to upgrade the platform from being remote-controlled to a fully autonomous tugboat with radio communications to an off-board computer. To prove sufficient autonomous behavior, we programmed our boat to be able to do several low-level
behaviors including wall following, obstacle circumnavigation, and autonomous docking and
undocking. To further showcase the boat’s autonomous capabilities, ”missions” utilizing
these low-level behaviors to create more complex behaviors were also added. Some missions
we sought out to achieve included making figure 8s around two obstacles and target capture,
which incorporates the boat’s programmed low-level behaviors.

In order to accomplish these objectives, our team used a three Arduino setup with hardware
serial communications between Arduinos, an XBee radio for communications between the
Arduinos and the off-board computer, three sonars, six long-range sharp IRs, an IMU shield,
and a Pixycam. In order to seamlessly integrate these additions to our boat, we also had
to make some mechanical modifications including various sensor mounts. In the process of
creating this tugboat, we also created various libraries that made it easier to interface with
the boat. Each sensor had a library, each low-level behavior was included in a "Tugboat"
object, and each high-level behavior was programmed in a separate "missions" library to
distinguish low-level behaviors from high-level missions. We also added in a robust teleoperated control system to prevent the boat from being stranded in case of failures on any of
the sensors.

This project was created along with my classmates Jordan Leadley, Everardo Gonzalez, and Robert Wechsler.

## Videos

#### Undocking & circumnavigation test
Measures distance from the wall with IR sensors and heading with an IMU to successfully undock, then make a lap around the test pool
  <style>.embed-container { position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; } .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }</style><div class='embed-container'><iframe src='https://www.youtube.com/embed/ErhXkYFsTJ4' frameborder='0' allowfullscreen></iframe></div>

#### Undocking & 3 figure-8s test
Measures distance from the wall with IR sensors and heading with an IMU to sucessfully undock, then make 3 figure-8s around obstacles in the test pool to test robustness
  <style>.embed-container { position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; } .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }</style><div class='embed-container'><iframe src='https://www.youtube.com/embed/WIVv6e_m0Sk' frameborder='0' allowfullscreen></iframe></div>

#### Undocking, 1 figure-8, then re-docking test
Measures distance from the wall with IR sensors and heading with an IMU to sucessfully undock, then make a single figure-8s around obstacles in the test pool. Uses a Pixycam to successfully redock the boat.
  <style>.embed-container { position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; } .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }</style><div class='embed-container'><iframe src='https://www.youtube.com/embed/jrWSk9W6jTE' frameborder='0' allowfullscreen></iframe></div>

## Photos
<center>
  {% include overlay.html
    file="/img/projects/tugboat/front.jpg"
    padding-top="5px"
    width="57%"
    id="front"%}
  {% include overlay.html
    file="/img/projects/tugboat/front2.jpg"
    padding-top="5px"
    width="42%"
    id="front2"%}
  {% include overlay.html
    file="/img/projects/tugboat/back.jpg"
    padding-top="5px"
    width="69.5%"
    id="back"%}
  {% include overlay.html
    file="/img/projects/tugboat/top.jpg"
    padding-top="5px"
    width="29.2%"
    id="top"%}
  {% include overlay.html
    file="/img/projects/tugboat/team.jpg"
    padding-top="5px"
    width="100%"
    id="team"%}
</center>

## Documentation
+ [View Source Code on GitHub](https://github.com/AmyPhung/FunRoboTugboat)
+ Report:
<center>
  <embed src= "/files/fun-robo/FunRobo_Final_Report_.pdf" width= "100%" height= "1000">
</center>
