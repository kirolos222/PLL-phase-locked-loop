this repository is made for the circuit design of a small PLL that work as frequency synthesizer from 100M to 5GHz 

first circuit is PFD circuit :

<img width="355" height="385" alt="image" src="https://github.com/user-attachments/assets/a741244b-df0d-4e04-9801-6ee7878c18ef" />

PFD circuit :

<img width="1625" height="495" alt="image" src="https://github.com/user-attachments/assets/3d677d32-6c9e-49e1-8011-a1f519aa3fb5" />

PFD D_flip_flop :

<img width="1733" height="644" alt="image" src="https://github.com/user-attachments/assets/15777c47-44ea-4f6d-ab6e-0aba639cbf54" />

there is a challenge in PFD that is the Dead Zone if the pulse is too small to switch open the charge pump so we need to introduce some delay in the reset path of the PFD but that will be done after designing the charge pump itself .

Charge Pump Test Bench:

<img width="1602" height="649" alt="image" src="https://github.com/user-attachments/assets/79178818-3e71-42c3-8f46-9258639e9141" />

PLL VCTRL look :

<img width="993" height="710" alt="image" src="https://github.com/user-attachments/assets/f4cada10-bc14-4ad4-a86b-ec314d9b471f" />

PLL frequency : 

<img width="1894" height="684" alt="image" src="https://github.com/user-attachments/assets/59438be8-1832-43e4-a566-bee45b595fa8" />

PFD+Charge_Pump Phase noise :

<img width="1919" height="642" alt="image" src="https://github.com/user-attachments/assets/eef4b7c0-3741-4e46-8040-805094b188e7" />

Phase_error due to PFD+Charge_Pump :


