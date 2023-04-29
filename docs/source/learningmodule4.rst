NG-Core Overview
=================================

Abstract
---------
The next-Generation Core network, or NG-Core, is an important technology for 5G networks. The NG-Core is responsible for managing and routing data traffic. Some of its responsibilities include authentication, IP connectivity, and bill tracking. Another feature includes Network Function Virtualization, or NFV, which improves efficiency. Another name for the NG-Core technology is a 5G Mobile Core.

Mobile Core Basics
------------------
* The “User Plane” (UP or UPF) forwards traffic between RAN and the Internet
* UPF is responsible for policy enforcement, QoS policing, traffic usage statistics, and lawful intercept
* The majority of the functionality comes from these two:

    * AMF (Core Access and Mobility Management Function) - responsible for handling connection and mobility management tasks
    * SMF (Session Management Function) - manages each UE session and takes care of things such as IP address allocation.

* Many smaller features need to be shown in the figure, as 3GPP defines a large array of control-related elements that serve to complete smaller tasks.

Authentication, IP Connectivity, and Bill Tracking
--------------------------------------------------

Base stations make up a large part of the radio access network (RAN) and play an essential role in communication. They are responsible for many tasks, including transmitting and receiving signals with user equipment. Base stations are also in charge of managing resources; this can include managing bandwidth, power, and time slots in accordance with user equipment. It also performs scheduling and interference management to ensure that users get the best possible connection. Base stations are also in charge of signal processing. This means that signals sent from the UE to the stations are decoded to ensure they are in a form suitable for information processing. Likewise, they are also responsible for encoding signals before transmitting them to UE. This adds a measure of security when transmitting data using 5G.

.. figure:: /images/5g-mobile-phone-mast.png
   :alt: 5Gdocumentation
   :align: center

   *5G Base Station*

Radio Technologies Utilized for 5G RAN
--------------------------------------

One of the technologies implemented in 5G technology is the use of millimeter waves. These waves are used to provide a high-speed, low latency connection especially when in urban areas where a high number of users are present. These signals don’t come without their limitations however. One limitation is the limited range that comes with these signals, meaning they are easily blocked by buildings and trees. These signals also have limited penetration, meaning on top of their limited range they also have hard time penetrating solid objects. This limits the use of this type of signal indoors. These signals are also susceptible to weather, such as rain, fog, and snow.
One of the ways to overcome this range of limitations is to use beamforming technology (previously mentioned under the 5G User Equipment module), which directs the signals to the UE. Beam

Quiz
----
.. raw:: html
    :file: Module4quiz.html
