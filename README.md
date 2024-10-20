# Amulanssi - Autonomous Medical Vehicle

## Inspiration

The inspiration behind **Amulanssi** came from a desire to revolutionize the medical technology space by creating a hardware solution that could potentially save lives. In critical moments, getting medical assistance to people as fast as possible can mean the difference between life and death. We envisioned a semi-autonomous, voice-controlled vehicle resembling an ambulance, one that could be dispatched quickly and efficiently to provide help in emergency situations. This concept blends cutting-edge technology with practical, real-world applications, and aims to enhance emergency response systems.

## What it Does

**Amulanssi** is a semi-autonomous, voice-controlled vehicle designed to function like an ambulance. It can respond to basic voice commands and navigate to a designated location with minimal human intervention. The vehicle is built with the goal of eventually becoming fully autonomous, enabling people to "call" it when in need of emergency medical assistance. The final vision is a system where users can request the vehicle through a simple voice command, and it will autonomously navigate to the patient’s location, providing essential care or transporting the patient to a nearby medical facility.

## How We Built It

We built the **Amulanssi** vehicle using **Arduino** as the core platform. The Arduino handles the car's movement, communication, and processing of voice commands through a Bluetooth module. We integrated various components, including:

- **Arduino microcontroller** for handling all car controls.
- **Bluetooth module** to receive voice commands and control signals from a mobile app or a connected device.
- **Motors and chassis** to drive the vehicle.
- **Sensors** to detect obstacles and assist in semi-autonomous navigation.
  
By leveraging Arduino’s flexibility and compatibility with various modules, we were able to implement semi-autonomous features and voice control functionalities for the vehicle.

## Challenges We Ran Into

One of the major challenges we encountered was the **Bluetooth connection** constantly disconnecting. This made the voice control function unreliable at times, which was critical for our car’s operation. After numerous tests and troubleshooting, we adjusted the code to improve Bluetooth stability but recognized that more work is needed to make the system reliable for real-world use. Additionally, refining the vehicle's navigation to accurately follow commands without frequent manual intervention proved to be a challenging task.

## Accomplishments That We're Proud Of

Despite the challenges, we are proud of how we were able to **wisely manage our time** and successfully build a functional semi-autonomous car within the constraints of the hackathon. We created a working prototype that responds to voice commands and can navigate autonomously to a limited extent. Our perseverance and ability to quickly solve problems helped us bring the project to life.

## What We Learned

Throughout the development process, we learned a lot about working with **Arduino** and the **serial libraries** needed to handle Bluetooth communication. We also gained a deeper understanding of how to integrate multiple hardware components such as motors, sensors, and communication modules. Our experience with voice control systems expanded as well, as we explored ways to make the system more responsive and reliable. Furthermore, this project taught us the importance of overcoming hardware challenges and the need for robust testing.

## What's Next for Amulanssi

The next phase for **Amulanssi** is to take the vehicle from **semi-autonomous** to **fully autonomous**. We plan to integrate more advanced sensors (like GPS, LIDAR, or ultrasonic sensors) to enhance the car’s navigation capabilities, enabling it to operate without any manual intervention. Additionally, we aim to improve the **Bluetooth communication** system and explore alternate wireless technologies for a more stable connection.

Our vision is to develop a vehicle that can autonomously navigate through urban environments, responding to **voice-activated calls** from people in need. We also plan to add more medical functionalities, such as integrating medical supplies or equipment within the vehicle, turning it into a comprehensive emergency response tool.

## Hackathon Experience

**Amulanssi** was developed during the **OmniHacks 2019** hackathon. This 24-hour hackathon provided the perfect environment for rapid prototyping and innovation. Despite the time constraints and technical challenges, our team was able to build a fully functioning semi-autonomous vehicle that demonstrates the future potential of autonomous medical technology. You can learn more about the hackathon at [OmniHacks 2019](https://omnihacks19.devpost.com/).

## How to Use

1. **Clone the repository** to your local machine:

git clone https://github.com/1300Sarthak/Amulanssi.git


2. **Set up the Arduino environment:**
- Install the necessary libraries for Bluetooth and motor control.
- Connect the Arduino microcontroller to the car chassis.
- Attach the motors, sensors, and Bluetooth module as per the schematic provided in the documentation.

3. **Upload the code** to the Arduino:

Open the .ino file in the Arduino IDE and upload it to your microcontroller.


4. **Control the car:**
- Use the connected device (phone or computer) to send voice commands via Bluetooth.
- Test the semi-autonomous mode by navigating the car around obstacles.

5. **Test and Debug:**
- Fine-tune the car’s sensors and voice commands by adjusting the parameters in the Arduino code.
- Troubleshoot any Bluetooth connection issues by following the steps in our documentation.

## Built With

- **Arduino** – Core microcontroller platform for controlling the car.
- **Bluetooth Module** – For receiving voice commands from a mobile device.
- **Motors and Sensors** – To handle the car’s movement and detect obstacles.
- **Voice Control Software** – To interpret voice commands and control the vehicle.

## Contributors

- **Sarthak Sethi** – [GitHub](https://github.com/1300Sarthak)
- **Team Members** – Additional contributors and developers who helped with hardware and software integration.

## Acknowledgments

We would like to thank the **OMNIHACKS hackathon organizers** for giving us the opportunity to bring this project to life. A special shoutout to the **Arduino community** for providing excellent resources and support that made it easier to work with hardware components.
