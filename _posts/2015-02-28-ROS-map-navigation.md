---
layout: post
title: ROS Map Navigation
subtitle: A simple ROS package to navigate a robot through a map
tags: [Software-Design]
---

My friends and I wanted to learn more about [SLAM](https://en.wikipedia.org/wiki/Simultaneous_localization_and_mapping), so we thought it'd be a good idea to use the final project in our Software Design class to get a headstart in learning about what goes into this complex problem. We first used the ROS package [hector_slam](http://wiki.ros.org/hector_slam) to get an idea of what a complete implementation would look like. After getting this up and running on the [TurtleBot](https://www.turtlebot.com/), we decided to focus on the map navigation component of SLAM since that fit within the scope of this class.

We first used the ROS package [gmapping](http://wiki.ros.org/gmapping) to generate a map, then we used our ROS package based on [nav2D](http://wiki.ros.org/nav2d) to find a path from the specified starting position to end goal on the map.

<style>.embed-container { position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; } .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }</style><div class='embed-container'><iframe src='https://www.youtube.com/embed/Fnh2aS3DxgY' frameborder='0' allowfullscreen></iframe></div>

+ See project website here: <https://amyphung.github.io/SLAM-SoftDes-Final-Project/>
+ See source code here: <https://github.com/AmyPhung/SLAM-SoftDes-Final-Project>
+ See code documentation here: <https://github.com/AmyPhung/SLAM-SoftDes-Final-Project/wiki>
