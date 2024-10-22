# CS-350
SNHU CS-350 Emerging Systems Architectures & Technologies

## Summarize the project and what problem it was solving.
The project involved developing a prototype smart thermostat for SysTec using a TI development board. This prototype uses a TMP006 temperature sensor to read room temperature, LEDs to indicate heating status, and buttons to adjust the set temperature. Data is simulated and sent to the server via UART, while a task scheduler manages operations. The project also includes an analysis of hardware architectures from TI, Microchip, and Freescale(NXT) to recommend the best solution for cloud connectivity via Wi-Fi, meeting the thermostat's business requirements for peripheral support, memory capacity, and connectivity.

## What did you do particularly well?
One of my greatest strengths is my ability to persevere through adversity. In this project, I encountered several challenging hurdles, particularly with the timer interrupt. I successfully overcame these by recognizing the importance of keeping the code executing inside the interrupt to a minimum.

## Where could you improve?
An area where I could improve is my overall knowledge of the field. Many of the challenges I faced were due to a lack of understanding, but once I acquired the necessary knowledge, the issues became much easier to resolve.

## What tools and/or resources are you adding to your support network?
To strengthen my support network, I'm adding tools like online documentation, coding forums, and resources such as technical guides and tutorials. I'm also seeking advice from mentors and peers in the field, leveraging communities like Stack Overflow, and using version control tools like Git to track progress and collaborate effectively. Additionally, I plan to explore educational platforms and professional networks to expand my knowledge base.

## What skills from this project will be particularly transferable to other projects and/or course work?
Skills from this project that will be highly transferable include writing efficient embedded system code, handling hardware-software interactions, and troubleshooting issues like timer interrupts and peripheral integration. Additionally, working with protocols like I2C and UART, using task scheduling, and applying coding best practices will be valuable in future projects. The experience of analyzing and comparing hardware architectures will also aid in making informed decisions in other embedded systems or IoT-related coursework.

## How did you make this project maintainable, readable, and adaptable?
I made this project maintainable, readable, and adaptable by applying coding best practices such as clear formatting, consistent commenting, and modular code structure. By organizing the code into well-defined functions, I ensured that each part had a specific purpose, making it easier to update or debug. I also used descriptive variable names and documented the code extensively to ensure that future developers or teammates can easily understand and modify it. Additionally, I kept the logic flexible, allowing for changes in hardware or software requirements without needing a complete overhaul.
