# APM Planner

[APM Planner](http://planner2.ardupilot.com/) 2.0 is an open-source ground station application for MAVlink based autopilots including [Erle-Robotics](http://erlerobotics.com) products that can be run on Windows, Mac OSX, and Linux.

![APM planner logo](../img/GCS/apm_planner_logo.png)

###Installation

You can download APM Planner in the next links:

* [Linux](http://planner2.ardupilot.com/wiki/installation-for-linux/)
* [Windows](http://planner2.ardupilot.com/wiki/install-windows/)
* [Mac](http://planner2.ardupilot.com/wiki/mac-install/)

###Connecting to Erle-Brain/Vehicles

Once you have installed the APM planner in your computer, the next step is to make connection between you computer and [Erle-Brain](http://erlerobotics.com/blog/erle-brain).

When you power up [Erle-Brain](http://erlerobotics.com/blog/erle-brain) or a vehicle/drone that contains this product, it automatically generates a WiFi spot and sets a telemetry port (11.0.0.2:6000) in order to exchange data with the GCS.

Follow the next steps to connect:

* Connect to WiFi, normally called **erle-copter** or **erle-brain**. The password is **holaerle**.
* Open APM Planner.
* Open **Communication** tab, and click on **Add Link -> UDP**
* Clik on **Add IP** and set it to **11.0.0.2:6000**, as in the next image:

![APM UDP](../img/GCS/apm_udp.png)

* Click on **Connect**
* Restart APM

Now the connection should be established automatically. If is not clear enough, you can watch [this video](https://www.youtube.com/watch?feature=player_detailpage&v=pKJyeTF_Qbo#t=69)!

###APM Planner basics

#####Flight Data Display

Thanks to the **primary flight display**, user can see the orientation of the drone and its inclination.

![Display](../img/GCS/apm_primary_display.png)

**Info View** subpanel contains a lot of useful information. In the first tab, you can see some basic parameters of your flight: the altitude, pitch, roll and yaw in degrees, ...

![InfoView](../img/GCS/apm_infoview.png)

In the **Action** tab, you can arm the drone, select the flight mode, send the the drone to a waypoints,...

![Actions](../img/GCS/apm_action.png)

In the **Messages* subtab you can read the messages sent using MAVlink. This messages are useful in order to know in which state is the autpilot.

![Messages](../img/GCS/apm_messages.png)



