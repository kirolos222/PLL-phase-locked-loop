this repository is made for the circuit design of a small PLL that work as frequency synthesizer from 100M to 5GHz 

first circuit is PFD circuit :

<img width="355" height="385" alt="image" src="https://github.com/user-attachments/assets/a741244b-df0d-4e04-9801-6ee7878c18ef" />

PFD circuit :

<img width="1625" height="495" alt="image" src="https://github.com/user-attachments/assets/3d677d32-6c9e-49e1-8011-a1f519aa3fb5" />

PFD D_flip_flop :

<img width="1733" height="644" alt="image" src="https://github.com/user-attachments/assets/15777c47-44ea-4f6d-ab6e-0aba639cbf54" />

there is a challenge in PFD that is the Dead Zone if the pulse is too small to switch open the charge pump so we need to introduce some delay in the reset path of the PFD but that will be done after designing the charge pump itself .

Charge Pump Test Bench:

<img width="619" height="450" alt="image" src="https://github.com/user-attachments/assets/ff1f6374-8239-4a0f-85a3-ddf6134b84e2" />

PLL VCTRL look :

<img width="993" height="710" alt="image" src="https://github.com/user-attachments/assets/f4cada10-bc14-4ad4-a86b-ec314d9b471f" />

PLL frequency : 

<img width="1894" height="684" alt="image" src="https://github.com/user-attachments/assets/59438be8-1832-43e4-a566-bee45b595fa8" />

PFD+Charge_Pump Phase noise :

<img width="1919" height="642" alt="image" src="https://github.com/user-attachments/assets/eef4b7c0-3741-4e46-8040-805094b188e7" />

Phase_error due to PFD+Charge_Pump :
Feedback_signal_width :

<img width="1913" height="575" alt="image" src="https://github.com/user-attachments/assets/5100bdf3-cfa6-4664-a29c-93843cb1c93e" />

Refernce_signal_width :

<img width="1919" height="634" alt="image" src="https://github.com/user-attachments/assets/73aeac09-a988-4e35-ae48-ee1a0242a36e" />

phase error is about 21.6661 ps

#VCO Design :
I wanted to design an LC tank so i followed this playlist 

https://www.youtube.com/watch?v=2t3dR2PLoDI&list=PL9Trid0A4Da1lh5hRCjpYMCDADtVXA9qU&index=4

the best way to explain limit cycle is using limit cycles that visualize it.

also this link for professor ali hajimiri is brilliant :

https://youtu.be/wByzymJ0Ppc?si=DJlanXC0hfwBPCo-

also this paper gives a good perceptive about phase noise in PLL system overall :

https://designers-guide.org/analysis/PLLnoise+jitter.pdf

VCO Design steps :
