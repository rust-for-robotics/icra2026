---
sequence_id: 2
speaker: Angelo Corsaro
time: 09:15 – 09:45
title: "ROS-Z:  Making ROS 2 Zenoh-Native"
# webpage: https://jane.doe
# affil: Buzz University
# affil_link: https://buzz.edu
img: angelo.png
# affil2: BuzzFizz Corp
# affil2_link: https://buzzfizz.corp
---

ROS 2 was designed to be independent from the underlying communication middleware. This is a nice architectural property, yet it does not come for free. When contributing to the development of the Zenoh RMW, we could not stop asking ourselves, what would happen if we were to remove these layers and have Zenoh-native RCL-C and RCL-Rust implementations. We decided to undertake the effort of building such a stack, named ROS-Z.