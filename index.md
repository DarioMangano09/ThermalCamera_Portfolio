# Thermal Camera
I built a thermal camera that can read levels of heat using a Raspberry Pi.The thermal camera displays a live video feed that can measure temperature from -40 degrees to 300 degrees. The biggest challenge was figuring out the code. I ran into many issues along the way, but after some struggle, I figured it out, and it worked smoothly. One of my biggest triumphs was getting the wiring to work on the second try. I have never used a breadboard, and this was my first time. After looking at a diagram of how a breadboard is connected, I did the wiring, and it worked. 


| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Dario M |  Archbishop Molloy | Electrical Engineering | Incoming Junior

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](Photo.jpg)
  
# Final Milestone Video

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Final Milestone
Since my previous milestone, not much has changed. I have tried to implement a modification where you can stream the video output and click anywhere on the thermal camera video and it will show its exact temperature. However, I ran into many issues that couldn't be resolved within this final week. I plan to implement this idea once the program is finished and I will continue to work on it. My biggest challenge at BSE was starting off. First few days were difficult because a lot of what my project needed, I did not know how to do. I have never used complex code like this and I also never built electrical systems so starting off felt overwhelming and stressful. Throughout the 3 weeks, I have grown comfortable with complex coding and I also gained lots of knowledge in the electrical engineering space. One of my biggest triumphs was getting my final modification to work. I spent a long time on the code and it worked. Unfortunately, the next day the code gave me many issues and I am still debugging. Some key topics I learned were Python coding, electrical wiring, and the uses of a Raspberry Pi. I learned about useful Python skills such as using virtual environments and installing libraries. In the electrical engineering space, I learned how to use a breadboard and what different types of wires do. In the future I hope to learn more complex electrical systems. My project did not have much electrical wiring so possibly in the future I will choose a project that is more electrical-focused.

# Second Milestone Video
<iframe width="560" height="315" src="https://www.youtube.com/embed/3P9qE5royps?si=Z5EV61mCDqmXFViq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

# Second Milestone
This week I worked on the hardware aspect of modifications. I added an external battery source so that the person using this product can walk around with it freely. I have also added a small monitor so that you can see the live video feed in your handheld device instead of looking at a big, heavy computer monitor. Something that has been surprising about the project for me was how technical it was. I was not expecting the amount of code required, but I am glad it was necessary because it has improved my coding abilities. A previous challenge I faced was navigating different parts of the terminal. I didn't know what specific things were used for, and figuring out what different libraries did was a struggle; however, I now feel more confident working with the terminal. The final step that needs to be completed before my final milestone is implementing the final modification. I want to be able to click anywhere on the thermal camera feed and see what its exact temperature.


# First Milestone Video
<iframe width="560" height="315" src="https://www.youtube.com/embed/8vxd8xakxFM?si=FmGbtBPXE4TS3fMx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

# First Milestone
My project is the thermal camera using a Raspberry Pi. I plan to build it by connecting the thermal camera to the  Raspberry Pi using a breadboard and then coding it using Python and using a virtual environment to run the code and get the thermal camera live video feed. The components I have used so far are the Raspberry Pi 4, breadboard, and the MLX90640 thermal camera. I have successfully wired the components together, and I have finished the coding to get the thermal camera live feed. One challenge I would like to solve in the future is giving a smoother video because currently the video is quite laggy. I would also like to modify my project by adding a small monitor or display that someone can transport around with the camera.

# Code
```
import pithermalcam as ptc
ptc.test_camera()
ptc.stream_camera_online()
```


# Bill of Materials

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| MLX90640 | Thermal imaging camera | $70 | <a href="https://www.amazon.com/Waveshare-Thermal-Camera-Communicating-Interface/dp/B07ZKJPZ7Z/ref=sr_1_1_sspa?adgrpid=1340305246887385&dib=eyJ2IjoiMSJ9.xxgAyYRQ2N7gXAl_rkWaiAbUNTq9ir7xL_FF7lnbVPZ1BIG-Xy9Jg1PnjPEQffj65afKbd81MZNi_Mxmvi43hTXkcIMCXt5QoTCOrMMZgemlI63marDnXslgVrNQgXlq33TfXZpeN9HpdAuLiXYVOzQWwb3FOY4KI38Ae1H96Dq83oWXFRgdZttz7IxRpGNmu1k6BjweNoAReUUuBkb4dg4N3IIQ9p3XcI3FNK4gwYk.UK9NfZ9ZlMiD4XuFUiyJxBDsJbVqzzhk9D_Y-32_68I&dib_tag=se&hvadid=83769226921656&hvbmt=be&hvdev=c&hvlocphy=97514&hvnetw=o&hvqmt=e&hvtargid=kwd-83769441762666%3Aloc-190&hydadcr=26613_11648999&keywords=mlx90640&mcid=120283e4638d3711b8761f76ac2a1eba&msclkid=fc461f552c0d1e2f6fd3773ae2d00dd6&qid=1752158027&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1"> Link </a> |
| Raspberyy-Pi 4 | Thermal camera runs off the Raspberry pi | $64 | <a href="https://www.amazon.com/Raspberry-Model-2019-Quad-Bluetooth/dp/B07TC2BK1X/ref=sr_1_1?crid=2TK0HKSG8KGZ8&dib=eyJ2IjoiMSJ9.HavuMzOx0pibLLpdWCmY00k6Sz1h7IjNXYchbCG7xmdC3tTHtLhOYVdjowONRCydAzPFDxep03wCpdTpyF15O3qpVOrfhGlwS5T7UusBjKpSjjwuU4toSGzLFXKSnu9Stk4yqTyvFp2SOtpmr6pytkPVxwe0i5pWF9JxhhJrgl5Wn4_lopZDRSUoI-VLVS_OlaCU1-YrYYoRQZZN-HQwAImeQ_lHvKpaWixnpv_8WcI.ubn2Ep7iLPe90hjeV6poYNxJ4BY7lyx5oSWzCHzC1wo&dib_tag=se&keywords=raspberry%2Bpi%2B4&qid=1752158166&sprefix=raspberry%2Bpi%2B4%2Caps%2C99&sr=8-1&th=1"> Link </a> |
| Breadboard | Connects thermal camera with Raspberry pi through wires| $7 | <a href="https://www.amazon.com/ELEGOO-Breadboard-Solderless-Breadboards-Electronics/dp/B0CXF1B6GB/ref=sr_1_2_sspa?crid=2ZR7B90H10DII&dib=eyJ2IjoiMSJ9.qSRroSxKFdd8V4RwgnQiFGWmZcmB-k9IWTnY6yg2XAgvwl18SDlMTuNv_1HnNdBo5ruyzLrcnpPcEKl80Fm8ljs6lxBAvTkCMSoAQqomMvm144S9bTUW2W_-jWC1Ii5r9zzbuGu5J-a-kihJn5_HcgjM-IL_p7nWm8IJsg4Gxx8ECzg24-2CUi5wQXw8Un5xjV_pakmU37P7lamq_jUvz8NLY9uPsMaZ9fRTRvb3pxk.aQ_J2FXPo2nzi1YvCbwampjBGFUWzEqohFokvp7ksdA&dib_tag=se&keywords=breadboard&qid=1752158571&sprefix=breadboard%2Caps%2C103&sr=8-2-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1"> Link </a> |
| STEMMA QT / Qwiic JST SH 4-pin Cable with Premium Female Sockets | Cables needed to connect thermal camera to breadboard | $1 | <a href="https://www.adafruit.com/product/4397"> Link </a> |
| 7 inch display | Display for the Raspberry pi | $35 | <a href="https://www.amazon.com/HMTECH-Raspberry-Pi-Monitor-Non-Touch/dp/B09MFNLRQQ/ref=sr_1_3?crid=RA2GWS47DKXA&dib=eyJ2IjoiMSJ9.IKhI7OF-6C-YxJ83UKh7T8Boi6vf2WNLjYT6Bmixd17GktVeaERKenM0C8vOH-pUSVOyYsGuzkGSxC4y2KUVuGK2QJutYcXlKjna9POA1Abg_2tTQy55fQWdLcAHUNKGrXhV2IbVdjypNBoImL67ISkpvk-IMEdIEpYjq71hobmE2WM1MDghrTEQjRRGmIQtlurjzTnXyBzBYIEx44s0nYml-XQ91zGsoZEicw5Re9Y.1qZYbothNB48WJV7E_ClfnQ13JaIadi-54F3-BTNZUA&dib_tag=se&keywords=7%2Binch%2Bmonitor&qid=1753450667&sprefix=7%2Binch%2Bmonitor%2Caps%2C136&sr=8-3&th=1"> Link </a> |
| Battery Pack | Allows the raspberry pi to get power without being plugged in to a wall | $26 | <a href="https://www.amazon.com/Anker-PowerCore-Ultra-Compact-High-Speed-Technology/dp/B01CU1EC6Y/ref=sr_1_3?crid=1M4Q9H42NY7TY&dib=eyJ2IjoiMSJ9.7kffm9Gz9cO9Ch3MoIgbWRTWieVyUqIKZfc5yHyfUf6ie9G9c-LP9iUG9qSncw-otQBA2i-b0K2i1IFFrHj1QMLiHgWqO79Zbd5mXPTTHhl-bv26by34pvkP74ZHgo27-hWJTq7fDBVOBH9jNC4qQq2cIrdAE1knBxtnDiGAErqsWpA2DYFYuvUrIYnj8WOmb52ywEFkYYZN0KMppBsOSYP0y2t0f11r2abkNAXPT9k.8I5BzgU51tyCHqbaEMpElC8dWWlIEpGSg6blLlc1Ll0&dib_tag=se&keywords=cylinder%2Bbattery%2Bpack&qid=1753451020&sprefix=cylinder%2Bbattery%2Caps%2C86&sr=8-3&th=1"> Link </a> |



