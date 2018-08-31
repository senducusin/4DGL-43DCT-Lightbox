# Lightbox
A simple microcontroller-based project using 4D Systems' gen4 touchscreen display module and some LED strips. This setup can be used to create a DIY lightbox for photography, a lightbox can be used to capture photos and videos of small objects or models with the feature to control the lightings or brightness of the background. 

## About the Project

* This project aims to create a functional lightbox circuit, with the ability to control the brightness of each individual LED-strip node thru the sliders on the touchscreen display with the use of 4DGL.

* This project uses a Workshop4 Pro feature: Smart Widgets

* This project uses the PWM pins of the gen4-PA to control the LEDs brightness through touch.

* Additional light nodes can be added on the circuit to improve and perform a more complex lightings as to what the user needs.

### Parts list

```
1 gen4-uLCD-43DCT-CLB   
1 gen4-PA and FFC Cable
1 uSD Card (at least 4gb, c10)
2 LM324N OP-AMP
1 5050 LED Strip
1 12v PSU
1 5v PSU

4 Opto-isolator
3 2N222 NPN Transistor
3 D288 NPN Power Transistor

6 10k ohms 1/4w Resistor
3 1 ohm 1w Resistor

0.1 uf non-polarized capacitor
```

## Schematic Diagram

https://www.digikey.com/schemeit/project/lightbox-HGDH1TG400TG/

## Built with

Workshop4 IDE (Visi Environment): https://www.4dsystems.com.au/product/4D_Workshop_4_IDE/

## Links

```
https://www.4dmakers.net/projects/details/lightbox
https://www.youtube.com/watch?v=EgZ1Fg-C8aQ 
```

## Author

* **Jansen Ducusin** - *Initial work* - [Senducusin](https://github.com/senducusin)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details