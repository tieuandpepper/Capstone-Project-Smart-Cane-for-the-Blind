# Capstone-Project-Smart-Cane-for-the-Blind

Undergraduate Senior Design Project - Smart Cane for the Blind

PROBLEMS: the traditional white cane has not changed for over 100 years. With the current technologies, we can better assist the visual impaired, improving their independent mobility. There are some products currently on the market, such as WeWalk. However, they are not accessible to the majority due to its cost.

PURPOSES: We were intended to create an affordable yet "smart" cane that could help the visual impaired "see" a little further than the reach of their cane.

FINAL PRODUCTS: We designed and built a cane that is equipped with camera and TOF (time of flight) sensors to "see" the surrounding and alert its user of impending obstables. The brain of the cane is a Raspberry Pi Model B with 2GB RAM. It has two distance feattures: detect obstacles and alert the user.

It used a machine learning algorithm to detect objects within 2 meters. Of course, it could detect objects further than that but it was costly in term of memory and computing time. ALso, since it's not possible to detect distance using a camera, two distance sensors were used to trigger the object detection algorithm when the detected distance was within 2 meters. 

To alert the user, the cane is equipped with two haptic motors and a speaker. In public areas or crowded places, a headphone can be used in place of the speaker. There is a 3.5mm audio output jack on the Raspberry Pi. The haptic motors were attached to the handle. Their vibration is based on the direction of detected object (left or right); they can vibrate at the same time. The intensity of the vibration increased as the detected distance decreased.
