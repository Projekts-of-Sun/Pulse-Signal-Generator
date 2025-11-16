Project: Digital Pulse Generator (KiCad E.D.A. 8.0.2):

1. **Key Features & Technical Details:**  
   There are in this folder the codes of the test program, which implement two types of tests:

   - **Microcontroller Control:**  
      The core of the design is an STM32F030F4Px microcontroller, responsible for the precise generation and control of the output pulses.
     
   - **USB Connectivity:**  
      The integration of an FT230XS USB-to-UART converter allows for easy connection to a host computer (p. 1). This facilitates configuration and debugging without requiring complex USB firmware programming.

    - **Optical Signal Transmission:**
     The circuit includes optical transmission and reception components (HFBR-1521 transmitters and IR26-21C_L110_TR8 LEDs/receivers) (p. 1). This indicates the capability for galvanic isolation or the output of optical signals (e.g., via fiber optics).

    - **Power Supply:**
     The board supports a dual power supply system with +3V3 and +5V to ensure flexibility when integrating into different systems.
 
   - **User Interaction:**
     Several buttons (SW1-SW5) and a 6-pin header (JP3) provide options for local control and external expansions.

3. **Project Contents:**
   
   - Schematic: Circuit design of the pulse-generator module
   
   - Footprint: Custom pads and mechanical definitions
  
   - Layout: Routed two-layer board with structured design
  
   - 3D Model: Visual representation of the assembled board

5. **Software & Design Tools:**  
   The entire design was developed using software KiCad E.D.A. 8.0.2, which ensures the traceability and adaptability of the schematic.
