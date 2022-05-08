# Modules__In_ECE_Power_HW
The circuit seen in Constant Linear Voltage Regulator.dch uses a MAX1818eut18#tg16 IC as its linear regulator. This IC is a low-dropout linear regulator with an adjustable output type. For this circuit, the minimum voltage required for proper operation is 2.5V, which must be provided between the IN and GND pins on the IC.
•	Vcc: 5V
•	CIn: 4.7uF 
•	COut: 10uF
•	ROut: 70Ω
•	RLoad: 100Ω
Users can adjust the RLoad resistor to simulate a greater strain on the system while also updating Rout to make sure the system is still operational. This will allow the user to manipulate the voltage across the device to equal the minimum amount allowed. This specific IC can source up to 500mA.
The adjustable voltage linear regulator seen in Adjustable Linear Regulator.dch uses the LM317 IC, seen as the component U1. This is an adjustable three pin voltage regulator IC with a high output current value of 1.5A. Pin 1 is the Adjustable pin through which Vout can be manipulated by connecting the resistor divider circuit. Pin 2 is the Output for Vout. Pin 3 is Input for Vin. The circuit itself is simple, C1 is used to filter the DC input voltage and feeds it to the Vin pin of the LM317 IC. The adjustable pin is connected with the two external resistor and connected with the Vout pin of the IC. The capacitor C2 is used for the filtering the output voltage received from the Vout pin. And then the output voltage received across the capacitor C2. This specific circuit would be useful in designs that want to produce and adjust a DC output within a certain voltage range.
•	Vcc: 9V
•	C1: 1uF 
•	C2: 0.1uF
•	R1: 10kΩ
•	R2: 330Ω
•	B1: +88.9V
The user can adjust the value of the potentiometer, R1, in order change the DC output value of the circuit.
