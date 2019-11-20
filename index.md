---
driveId1: 1pdMBRztl4hwKFFMda4EoZ6XhpAiQghke/preview
driveId2: 1pHAvKCSAgY-w3V80y9I5JjP0sdlyXCQQ/preview
driveId3: 1Tl2q_jN5x5cwon-ct0pOBudXi6bdHK-C/preview 
driveId4: 1wy18mJzV89NTWS7Uokwwevfwn35skPVR/preview
driveId5: 1GBqwwpeY2upPt3kuTuVRmDQpJm_MezkN/preview
driveId6: 13MsciUHUxg6Bi01xW0i_7wz9-W1oDOE-/preview
driveId7: 1kf_8a1-f6TvK-Yg2CHN3vY4D2lhtamOV/preview
driveId8: 1k0uEFaRBMMGwSVCmTJ-xHnwsM3Q8cVAP/preview
driveId9: 1AD6GeEYTFk8amG-6WcKhF-m2ffvk6ddB/preview
driveId10: 1kgoj4-DIPWnjCGPY8Q1DZ7cNQqUdaDsm/preview
---
## Computer Animation

Following will take you to the embedded video for each of the assignments.


### Assignment 0

- Here we were supposed to rotate a 3D object within a time of 20 sec with the speed 50t translation on x and y and 15t rotation on y.


{% include assignment0.html id=page.driveId1 %}

### Assignment 1

- Here we put the framework for keyframe animation down. 

#### Linear interpolation on position and SLERP on rotation.
  
  {% include assignment0.html id=page.driveId2 %}
  
#### Linear interpolation on position and SLERP on rotation and ease-in ease-out mapping for u.
  
  {% include assignment0.html id=page.driveId3 %}
  
#### Catmullrom interpolation for position and SLERP on rotation.
  
  {% include assignment0.html id=page.driveId4 %}
  
#### Catmullrom interpolation for position and SLERP on rotation and ease-in ease-out mapping for u.
  
  {% include assignment0.html id=page.driveId5 %}
  
### Assignment 2
- Here we have implemented a billiards shot simulation
- As of now there is translation with one collision.
- I will update the video as it gets better. 
#### Billiards initial draft - A lot left to do.  
  
  {% include assignment0.html id=page.driveId6 %}  
#### Billiards final draft - 

- Rolling implemented, at pure rolling angular momentum driven by W= V/R.
- Oblique collisions implemented.
- Wall collision elastic (coefficient of restitution was causing balls to get stuck to the walls).
- Pockets not implemented due to shortness of time. 

 {% include assignment0.html id=page.driveId7 %}

### Assignment 3 : Mocap 

#### First Draft - Parsing of File to create joints and bones in hierarchy is Done


{% include assignment0.html id=page.driveId8 %}

#### Final draft
- Sneak and Jog bvh files used to test.
- BVH left coordinate system to Unity Right coordinae system logic taken from :https://gamedev.stackexchange.com/questions/140579/euler-right-handed-to-quaternion-left-handed-conversion-in-unity

- SNEAK:
 {% include assignment0.html id=page.driveId9 %}
 
 - JOG:
  {% include assignment0.html id=page.driveId10 %}
