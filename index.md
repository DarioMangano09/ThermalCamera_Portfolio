# Thermal Camera
I built a thermal camera that can read levels of heat using a raspberry-pi.The thermal camera displays a live video feed that can measure temperature from -40 degrees to 300 degrees. The biggest challenge was figuring out the code. I ran into many issues along the way, but after some struggle, I figured it out, and it worked smoothly. One of my biggest triumphs was getting the wiring to work on the second try. I have never used a breadboard, and this was my first time. After looking at a diagram of how a breadboard is connected, I did the wiring, and it worked. 

You should comment out all portions of your portfolio that you have not completed yet, as well as any instructions:
```HTML 
<!--- This is an HTML comment in Markdown -->
<!--- Anything between these symbols will not render on the published site -->
```

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Dario M |  Archbishop Molloy | Electrical Engineering | Incoming Junior

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)
  
# Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE



# Second Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 

# First Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/CaCazFBhYKs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


My project is the thermal camera using a raspberry-pi. I plan to build it by connecting the thermal camera to the  raspberry-pi using a breadboard and then code it using python and use a virtual enviorment to run the code and get the thermal camera live video feed. The components I have used so far is the raspberry-pi 4, breadboard, and the MLX90640 thermal camera. I have successfully wired the components together and i have finished the coding to get the thermal camera live feed. One challange I would like the solve in the future is giving a smoother video becuase currently the video is quite laggy. I would also like to modify my project by adding a small monitor or display that someone can transport around with the camera.


# Code
```
import pithermalcam as ptc
```
```
ptc.test_camera()
```
```
ptc.stream_camera_online()
```
Terminal:
dario@raspberrypi:~ $ source thermalcam-env/bin/activate
(thermalcam-env) dario@raspberrypi:~ $ python thermal_viewer.py
/home/dario/thermalcam-env/lib/python3.11/site-packages/adafruit_blinka/microcontroller/generic_linux/i2c.py:30: RuntimeWarning: I2C frequency is not settable in python, ignoring!
  warnings.warn(
Camera seems to be connected and returning a value:
Average MLX90640 Temperature: -10.1C (13.9F)
To verify it's working, change the average temperature
(e.g. by hold your hand over the camera) and run again to verify that the average temperature has changed.
Server can be found at 192.168.1.222:8000
 * Serving Flask app 'pithermalcam.web_server'
 * Debug mode: off


# Bill of Materials

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| MLX90640 | Thermal imaging camera | $70 | <a href="https://www.amazon.com/Waveshare-Thermal-Camera-Communicating-Interface/dp/B07ZKJPZ7Z/ref=sr_1_1_sspa?adgrpid=1340305246887385&dib=eyJ2IjoiMSJ9.xxgAyYRQ2N7gXAl_rkWaiAbUNTq9ir7xL_FF7lnbVPZ1BIG-Xy9Jg1PnjPEQffj65afKbd81MZNi_Mxmvi43hTXkcIMCXt5QoTCOrMMZgemlI63marDnXslgVrNQgXlq33TfXZpeN9HpdAuLiXYVOzQWwb3FOY4KI38Ae1H96Dq83oWXFRgdZttz7IxRpGNmu1k6BjweNoAReUUuBkb4dg4N3IIQ9p3XcI3FNK4gwYk.UK9NfZ9ZlMiD4XuFUiyJxBDsJbVqzzhk9D_Y-32_68I&dib_tag=se&hvadid=83769226921656&hvbmt=be&hvdev=c&hvlocphy=97514&hvnetw=o&hvqmt=e&hvtargid=kwd-83769441762666%3Aloc-190&hydadcr=26613_11648999&keywords=mlx90640&mcid=120283e4638d3711b8761f76ac2a1eba&msclkid=fc461f552c0d1e2f6fd3773ae2d00dd6&qid=1752158027&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1"> Link </a> |
| Raspberyy-Pi 4 | Thermal camera runs off the Raspberry pi | $64 | <a href="https://www.amazon.com/Raspberry-Model-2019-Quad-Bluetooth/dp/B07TC2BK1X/ref=sr_1_1?crid=2TK0HKSG8KGZ8&dib=eyJ2IjoiMSJ9.HavuMzOx0pibLLpdWCmY00k6Sz1h7IjNXYchbCG7xmdC3tTHtLhOYVdjowONRCydAzPFDxep03wCpdTpyF15O3qpVOrfhGlwS5T7UusBjKpSjjwuU4toSGzLFXKSnu9Stk4yqTyvFp2SOtpmr6pytkPVxwe0i5pWF9JxhhJrgl5Wn4_lopZDRSUoI-VLVS_OlaCU1-YrYYoRQZZN-HQwAImeQ_lHvKpaWixnpv_8WcI.ubn2Ep7iLPe90hjeV6poYNxJ4BY7lyx5oSWzCHzC1wo&dib_tag=se&keywords=raspberry%2Bpi%2B4&qid=1752158166&sprefix=raspberry%2Bpi%2B4%2Caps%2C99&sr=8-1&th=1"> Link </a> |
| Breadboard | Connects thermal camera with raspberry-pi through wires| $7 | <a href="https://www.amazon.com/ELEGOO-Breadboard-Solderless-Breadboards-Electronics/dp/B0CXF1B6GB/ref=sr_1_2_sspa?crid=2ZR7B90H10DII&dib=eyJ2IjoiMSJ9.qSRroSxKFdd8V4RwgnQiFGWmZcmB-k9IWTnY6yg2XAgvwl18SDlMTuNv_1HnNdBo5ruyzLrcnpPcEKl80Fm8ljs6lxBAvTkCMSoAQqomMvm144S9bTUW2W_-jWC1Ii5r9zzbuGu5J-a-kihJn5_HcgjM-IL_p7nWm8IJsg4Gxx8ECzg24-2CUi5wQXw8Un5xjV_pakmU37P7lamq_jUvz8NLY9uPsMaZ9fRTRvb3pxk.aQ_J2FXPo2nzi1YvCbwampjBGFUWzEqohFokvp7ksdA&dib_tag=se&keywords=breadboard&qid=1752158571&sprefix=breadboard%2Caps%2C103&sr=8-2-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1"> Link </a> |
| STEMMA QT / Qwiic JST SH 4-pin Cable with Premium Female Sockets | Cables needed to connect thermal camera to breadboard | $1 | <a href="https://www.adafruit.com/product/4397"> Link </a> |

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
