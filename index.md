---
layout: default
---

![alt text](https://github.com/jake-g/Vehicle-Infotainment-Center/raw/gh-pages/_images/banner.png)

# Vehicle Infotainment Center


#### Goal
Develop an open source UI infotainment platform for vehicles that communicates with vehicle hardware and cloud based services to deliver media, autopilot, driving statistics and diagnostics in order to enhance safety and user experience.

#### Impact
The automotive industry is flooded with dated, unintuitive technologies. With the growing number of open source projects and communities on the internet, now is a great time to help push the open source wave into the historically proprietary automotive market. Ford has recently opened some of it's technology by providing a very limited API, and Tesla is shattering standards by releasing patents. There has yet to be a truly open source, extendable infotainment system for vehicles. We want to change that.

## Functionality
#### Apps
* Phone
  * Bluetooth handsfree
  * Contact browser
  * Notification reader
* Music
  * Bluetooth Music Player
  * Cloud radio
  * Smart auto playlists
  * Mobile phone remote
* Navigation
  * Google maps and Waze
  * Smart Navigation (time vs money vs efficiency)
* Web Browser
* Notifications
  * Email
  * Calendar
  * Text

#### Features
* Autopilot features
  * Lane, backup, parking assist
  * Eye tracking
  * Optimization features
* Mobile Phone Integration
  * Web, IOS and Android client
  * Bluetooth handsfree
  * Music control
  * Climate control
  * Smart Charging
  * Find my car
* Visualization Metrics
  * Visual driver statistics
  * Hybrid vehicle mode display
  * Fuel efficiency
  * Battery information
  * Low fuel/charge indicator
  * Car diagnostics
* Vehicle control over CAN
  * Steering wheel buttons
  * Climate control
  * Various sensors

#### Design
The canvas will be a touchscreen interface with simplicity as the forefront of the UI. Unlike a phone which is always in near the users face, this will be a supplement the the driving experience and not a distraction. This means the design focus will be smoothness and ease of use rather than animations and flashy menus. All main functions must be easily accessible and executable with minimal driver distraction. If you have ever interacted with the UI of a modern car, you probably have noticed how dated, ugly and limited they are. We aim to bring the IOS and Android style interfaces that users are used to into the vehicle. Such interfaces will include the main screen, and a mobile app with the possibility of a HUD or cluster display. Additionally, we aim to provide elegant visual metrics to aid the driver in learning and improving their driving patterns.

#### Engineering
We have a pre-existing [Github repository](https://github.com/UWEcoCAR/UWCenterStack) with an old build to start from. This was written in Javascript and utilizes the Node webkit. It is run on a Debian linux kernel on a mini computer. Developers will use a distributed VM or embedded device for development. We are open to building off of this or starting from scratch depending on the team's input. We also have CAN drivers for interfacing with the lower level vehicle controls. We have plans for using python scripting for some of the backend media daemons and Google's maps api for navigation. Autonomous related features will likely utilize OpenCV and machine learning libraries in Python. Many of these elements are flexible and up for discussion. We are also looking into ReactJS by Facebook and the Electron runtime developed by Github to generate our web style frontend interface.

## Team
This project is a subset of the [UW EcoCAR 3](http://uwecocar.com/index.html) project which is a funded four year project that involves converting a 2016 Camaro into a cutting edge hybrid. The vehicle lab is located on the UW campus and will be accessible by those on the team. We will be using the Camaro as a test vehicle for the infotainment system, however the design intent is to design it to be compatible with all modern vehicles. Some features, like the Camaro autopilot, will require NDA's and need to remain private. This is because they rely on donated cutting edge hardware that we could never afford. We can eventually generalize our algorithms to work on generic hardware that anyone can use.

This is a university funded project, with learning as a priority. This doesn't necessarily mean you need to be a University student, but there will not be any pay compensation, at least for now. There are opportunities for school credit and internships/jobs. We do have a headcount limit, so if there is enough interest the application process may become competitive.

#### Team requirements
The team will be multidisciplinary and not very restrictive as to who can join. That being said, there are a few requirements listed below.

  * Self learner
  * Time to contribute
  * Idea of what you want to contribute

#### Roles
Here is a rough idea of the roles we will be filling. These roles will likely become small subteams

* Frontend
* Backend
* User interface Design (UI)
* User experience (UX)
* Embedded programming
* Project management (PM)

#### Skills
The outlined skills provide an idea of the projected disciplines and programming environments we plan on utilizing.  The skills listed are preferred but not a requirement to join but provide some insight into what we will be dealing with.

This is a software, hardware and design project driven by data and user experience.

* UI/UX design
* Linux and virtual machine familiarity
* Computer Vision and machine learning
* Knowledge of CAN protocol (UDS, ODX)
* Data visualization
* Adobe or Sketch design tools
* Programming
  * Javascript (node)
  * React Javascript
  * Electron or node webkit
  * CSS / HTML / JSX
  * Embedded C
  * Python
  * Google maps API
  * Cloud networking
  * IOS and Android
  * Matlab

#### Expectations
We expect a __minimum of 8 hrs per week__ from everyone on the team. UW EcoCAR team members considered as *dedicated* easily spend 30+ hours per week on the project. Those considered dedicated will likely have leadership and travel opportunities.

## Apply
You are highly encouraged to __[apply here](http://goo.gl/forms/DbPqCebwa7)__ as soon as possible before the team fills up.

After applying email <uw.infotainment@gmail.com> to say hi, share a resume, provide some info on past projects or outline what you want to get out of this.


#### 2016 Chevrolet Camaro
We get one of the first ones off the factory line and are making it a super fast hybrid! Yes, we will get to test it's top speed and all the features we are implementing.

__You__ can be part of this.

<br>
<div style="text-align:center"><img src ="https://github.com/jake-g/Vehicle-Infotainment-Center/raw/gh-pages/_images/cropped-camaro.png" /></div>

<br>
<a href="https://github.com/jake-g/Vehicle-Infotainment-Center">View project on <strong>GitHub</strong></a></li></div><div style="text-align:left">
