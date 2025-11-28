this repository is made for the circuit design of a small PLL that work as frequency synthesizer from 100M to 5GHz 

first circuit is PFD circuit :

<img width="355" height="385" alt="image" src="https://github.com/user-attachments/assets/a741244b-df0d-4e04-9801-6ee7878c18ef" />

PFD circuit :

<img width="1693" height="646" alt="image" src="https://github.com/user-attachments/assets/0ba021b6-6602-429b-9940-dadab45704ec" />

PFD D_flip_flop :

<img width="1733" height="644" alt="image" src="https://github.com/user-attachments/assets/15777c47-44ea-4f6d-ab6e-0aba639cbf54" />

there is a challenge in PFD that is the Dead Zone if the pulse is too small to switch open the charge pump so we need to introduce some delay in the reset path of the PFD but that will be done after designing the charge pump itself .

Charge Pump Test Bench:

<img width="1602" height="649" alt="image" src="https://github.com/user-attachments/assets/79178818-3e71-42c3-8f46-9258639e9141" />


