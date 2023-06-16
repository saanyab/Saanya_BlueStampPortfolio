# Third Eye For The Blind
I have developed a device with the potential to assist individuals who are visually impaired. This wearable technology enables blind individuals to navigate more easily by detecting obstacles in close proximity using ultrasonic waves. The device notifies the user through escalating buzzer sounds and vibrations from a motor, which intensify as the user approaches the detected object.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Saanya B. | James Logan High School | Bio Engineering | Incoming Sophomore

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)
  
# Final Milestone
For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Second Milestone
For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# First Milestone
I achieved my first milestone by successfully setting up and connecting the ultrasonic sensor and Arduino micro to the breadboard. This setup allowed me to test the functionality of the LED, vibrating sensor, and buzzer, as well as determine the necessary wiring connections. By utilizing jumper cables, I established a connection between the Arduino and the ultrasonic sensor, which was integrated with a switch that toggles between the buzzer and LED aspects of the programmed projection. Subsequently, I developed a code that displays the distance of an object in centimeters on the serial monitor, using the ultrasonic sensor. As the object approaches the sensor, the distance reading decreases, while it increases as the object moves farther away. This functionality relies on the sensor emitting sound waves that travel towards the object, then bounce back to the sensor, which in turn receives an echo. By analyzing the time it takes for the pulse to return, the sensor can accurately calculate the distance between itself and the object.

<iframe width="560" height="315" src="https://www.youtube.com/embed/CaCazFBhYKs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |

| Arduino Micro | Main Program Board | $10.95 | <a href="https://www.amazon.com/SparkFun-Arduino-Mini-328-3-3V-8MHz/dp/B004RF9LB8/ref=sr_1_5?crid=276NUJP5GVPNS&keywords=SparkFun+Arduino+Pro+Mini+328+-+5V%2F16MHz&qid=1686772444&sprefix=%2Caps%2C470&sr=8-5"> Link </a> |

| Perfboard | Project Assembled on Top of it | $9.99 | <a href="https://www.amazon.com/ELEGOO-Prototype-Soldering-Compatible-Arduino/dp/B072Z7Y19F/"> Link </a> |

| Ultrasonic Sensor | Main Sensor for Detection | $6.99 | <a href="https://www.amazon.com/WWZMDiB-HC-SR04-Ultrasonic-Distance-Measuring/dp/B0B1MJJLJP/ref=sr_1_3 crid=SMA11V06DTND&keywords=ultrasonic+sensor&qid=1686772587&sprefix=ultrasonic+senosr%2Caps%2C144&sr=8-3)"> Link </a> |

| 5mm Red LED | Used for Output of Program | $5.99 | <a href="https://www.amazon.com/Diffused-Lighting-Electronics-Components-Emitting/dp/B01C3ZZT0A/"> Link </a> |

| Solderless Breadboard | Used to Build Project On | $9.99 | <a href= "https://www.amazon.com/Breadboards-Solderless-Breadboard-Distribution Connecting/dp/B07DL13RZH/ref=sr_1_1_sspa?crid=2G0A3O6U8I453&keywords=solderless+breadboard&qid=1686772774&sprefix=solderles%2Caps%2C155&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1"> Link </a> |

| Slide Switch | Used to Toggle Between Haptic Sensor and Buzzer| $5.39 | <a href="https://www.amazon.com/HiLetgo-SS-12D00-Toggle-Switch-Vertical/dp/B07RTJDW27/"> Link </a> |

| Buzzer | Used to Switch Detection from Light to Sound | $6.88 | <a href= "https://www.amazon.com/Gikfun-Active-Magnetic-Continous-Arduino/dp/B01FVZQ6F6/ref=sr_1_2_sspa?crid=31I3JQE4NAJ8J&keywords=buzzer+arduino&qid=1686772919&sprefix=buzzer%2Caps%2C191&sr=8-2-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1"> Link </a> |

| Female Headers | Used to Connect Arduino and Sensor to Breadboard| $5.99 | <a href="https://www.amazon.com/HiLetgo-Single-Female-2-54mm-Vertical/dp/B00VVI1L1W/"> Link </a> |

| Vibrating Motor | Used to Give Physical Alert of Objects | $17.99 | <a href= "https://www.amazon.com/BestTong-Miniature-Vibrating-Vibration-Coreless/dp/B073NGPHDR/ref=sr_1_9?crid=3MKLV0J4PWN9X&keywords=vibrating+motor&qid=1686859468&sprefix=vibrating+moto%2Caps%2C200&sr=8-9"> Link </a> |

| Male Headers | Used to Connect Arduino and Sensor to Breadboard | $10.99 | <a href= "https://www.amazon.com/ZYAMY-2-54mm-Breakable-Straight-Connector/dp/B0778KCHHR/"> Link </a> |

| Jumper Wires | Used to Connect Components on the Breadboard | $9.99 | <a href= "https://www.amazon.com/MCIGICM-Breadboard-Jumper-Cables-Arduino/dp/B081GMJVPB/ref=sxin_17_pa_sp_search_thematic_sspa?content-id=amzn1.sym.6fd80408-71b6-44da-b059-082bba9089d3%3Aamzn1.sym.6fd80408-71b6-44da-b059-082bba9089d3&crid=3DIRCBWGHOZ6B&cv_ct_cx=jumper+wires&keywords=jumper+wires&pd_rd_i=B081GMJVPB&pd_rd_r=8948dacb-9531-4931-a76b-50be9ca669e2&pd_rd_w=hx8N0&pd_rd_wg=Vfast&pf_rd_p=6fd80408-71b6-44da-b059-082bba9089d3&pf_rd_r=XYNWGFWF0D205PQRWAMW&qid=1686859569&sprefix=jumper+wire%2Caps%2C185&sr=1-2-364cf978-ce2a-480a-9bb0-bdb96faa0f61-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9zZWFyY2hfdGhlbWF0aWM&psc=1"> Link </a> |

| Power Bank | Used to Provide Power to Arduino | $17.99 | <a href= "https://www.amazon.com/Anker-PowerCore-Ultra-Compact-High-Speed-Technology/dp/B01CU1EC6Y/"> Link </a> |

| Soldering Iron | Used to Solder Everything to the Breadboard | $16.99 | <a href= "https://www.amazon.com/Soldering-Kit-Temperature-Desoldering-Electronics/dp/B07GTGGLXN/"> Link </a> |

| Hot Glue Gun & Hot Glue Sticks | Used to Attach Things Together | $27.49 | <a href= "https://www.amazon.com/Gorilla-8401509-Hot-Glue-Sticks/dp/B088HF5ZQ1/"> Link </a> |

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
