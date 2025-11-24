this repository is made for the circuit design of a small PLL that work as frequency synthesizer from 100M to 5GHz 

first circuit is PFD circuit :

<img width="355" height="385" alt="image" src="https://github.com/user-attachments/assets/a741244b-df0d-4e04-9801-6ee7878c18ef" />

PFD circuit :

<img width="1313" height="641" alt="image" src="https://github.com/user-attachments/assets/752ace30-0895-4621-b711-2d44566400bc" />

PFD D_flip_flop :

<img width="1193" height="625" alt="image" src="https://github.com/user-attachments/assets/83a34ef9-dbbb-4f0f-9789-601f7a1e45df" />

there is a challenge in PFD that is the Dead Zone if the pulse is too small to switch open the charge pump so we need to introduce some delay in the reset path of the PFD but that will be done after designing the charge pump itself .

Charge Pump Test Bench:

<img width="1602" height="649" alt="image" src="https://github.com/user-attachments/assets/79178818-3e71-42c3-8f46-9258639e9141" />

