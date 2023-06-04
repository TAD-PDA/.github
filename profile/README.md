# The TAD (Type And Display)
The TAD is a portable, OSHW PDA, designed to be easily recreated in hobbyist conditions on the low cost.

# Driving design points
- Linux System: TAD runs on a Linux operating system, providing a familiar and powerful environment for developers and users.
- 60% Keyboard Design: TAD features a compact 60% keyboard layout, optimized for efficient typing and comfortable handheld use.
- Off-the-Shelf and Easily Ordered Parts: The TAD project leverages readily available and easily orderable components, making it accessible to a wide range of users.
- Low Price BOM: TAD aims to keep the Bill of Materials (BOM) cost under $100, ensuring an affordable option for those interested in building their own PDA.
- Extremely Customizable and Modular: TAD is built with modularity in mind, allowing users to customize, expand and simply tinker with their device according to their specific needs and preferences.



# How to get started

You will need:
- A Raspberry PI zero, zero W or zero 2.
- A 8+GB SD-card.
- An ST-LINK
- An SD-card reader/writer equipped device.
- PCB's from tad-hardware
- Parts as per BOM in tad-hardware
- 3D printed case from tad-hardware (Optional)
- STM32CUBEide
- Patience.


# Getting started

1. Collect and assemble the hardware from tad-hardware.
2. Burn usual Raspbian image onto your SD-card.
3. Copy files from tad-system-installer to /home/pi on your newly burned SD-card.
4. Run tad-installer on TAD over ssh.
5. Enjoy!
