---
title: Control Theory

has_children: false
has_toc: false
---

<!-- Page title (excluded from Table of Contents) -->
<h1>{{ page.title }}</h1>{: .no_toc }

{% include toc.html %} <!-- Table of Contents -->

## Videos

- [Control Bootcamp][control-bootcamp] - A very thorough video series on optimal
  control theory.

[control-bootcamp]: https://www.youtube.com/playlist?list=PLMrJAkhIeNNR20Mz-VpzgfQs5zrYi085m

## Articles

- [Brett Beauregard's Arduino PID Library][arduino-pid] ([Github Repo][arduino-pid-gh])
  \- A series of blog posts about writing a better PID library for Arduino. It
  can help expand your understanding of PID systems.
- [Stanford EE267 IMU Notes][ee267-imu] - Some notes from a class on virtual
  reality. Their choices of hardware is questionable but the math is solid.
  Section 5 and Appendix A are useful for learning about quaternions.
- [Understanding Euler Angles][euler-angles] - Detailed and well written page
  about euler angles.
- [Understanding Quaternions][quaternions] - An alternative to euler angles.
  More difficult, however it avoids the infamous problem of gimbal lock and
  other issues with euler angles.
- [Using Inertial Sensors for Position and Orientation Estimation][delft-paper]
  \- is a research paper by the brilliant people at Delft University of Technology

[arduino-pid]: http://brettbeauregard.com/blog/2011/04/improving-the-beginners-pid-introduction/
[arduino-pid-gh]: https://github.com/br3ttb/Arduino-PID-Library/
[ee267-imu]: https://stanford.edu/class/ee267/notes/ee267_notes_imu.pdf
[euler-angles]: https://web.archive.org/web/20210506165437/https://www.chrobotics.com/library/understanding-euler-angles
[quaternions]: https://web.archive.org/web/20210307022920/http://www.chrobotics.com/library/understanding-quaternions
[delft-paper]: https://arxiv.org/pdf/1704.06053.pdf

### Kalman Filters

A very useful filter that also is quite complicated

- [How a Kalman filter works in pictures][kalman-pictures]
- [Kalmanfilter.net][kalman-net]
- [The Kalman Filter][the-kalman]
- [A practical approach to Kalman filter and how to implement it][practical-kalman]
  ([Github Repo][practical-kalman-gh]) - Pretty detailed article about Kalman
  filters and how to use them in your code. Includes some C++ code and a library
  for easy Arduino implementation.

[kalman-pictures]: https://www.bzarg.com/p/how-a-kalman-filter-works-in-pictures/
[kalman-net]: https://www.kalmanfilter.net/default.aspx
[the-kalman]: https://engineeringmedia.com/controlblog/the-kalman-filter
[practical-kalman]: http://blog.tkjelectronics.dk/2012/09/a-practical-approach-to-kalman-filter-and-how-to-implement-it/
[practical-kalman-gh]: https://github.com/TKJElectronics/KalmanFilter

## Books

- [Control System Design: An Introduction to State-Space Methods][csd-state-space]
  by Bernard Friedland - An in depth book on state space modelling. Not
  recommended for beginners. (_Highly recommended by Joe Barnard_)
- [The Fundamentals of Control Theory][control-theory]
  by Brian Douglas - A fantastic, free ebook that gives an intuitive understand
  of the basics of control theory.

[csd-state-space]: https://www.amazon.com/Control-System-Design-Introduction-State-Space/dp/0486442780/
[control-theory]: https://www.patreon.com/posts/book-is-now-free-28313078

## PID Tuning Software

- [Anvil Tuner][anvil-tuner] by cheesefacejoe on the VPL discord - A free,
  open source tool designed to run a simple simulation of a TVC rocket flight.
  It allows the User to manually tune their PID controller to obtain rough
  values for their controller gains.

[anvil-tuner]: https://github.com/cheesefacejoe/Anvil-PID-Tuner
