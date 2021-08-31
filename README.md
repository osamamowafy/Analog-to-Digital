# Analog-to-digital

# Comparator

A comparator is a circuit that responsible to compare two input analog signals, and the output is a digital signal that indicating which signal is larger than the other, so it takes two analog inputs and the output is a digital signal. a hysteresis circuit is added to the comparator in order to minimize the noise on the output signal when the two inputs approach zero. the circuit is simulated on an open-source tool (xschem), INP, INN are the inputs of the comparator, EN signal for controlling the circuit and Vout is the digital signal which compares the two inputs, the figure below is the circuit of the comparator:

![Screenshot from 2021-08-30 15-56-26](https://user-images.githubusercontent.com/87280599/131502547-f5b01ade-3f33-434e-99b3-28273cab41e7.png)

The output and the input signals are shown at which shows the binary output is zero or one based on the comparison between the two signals:

![Screenshot from 2021-08-30 15-55-47](https://user-images.githubusercontent.com/87280599/131504534-fc590af9-facc-4fc3-b565-48dd333e9d7a.png)

The layout of the comparator is designed on an open-source tool called KLayout with Sky130 PDK libraries, the area of the layout is 17x12 µm^2. Physical verification steps include LVS & DRC are made in order to ensure the correctness of the layout design which shown below:  

![Screenshot 2021-08-31 145730](https://user-images.githubusercontent.com/87280599/131506515-91726b93-1f5b-4c41-b6b0-45e43c92f824.jpg)






