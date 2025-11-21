this repository is made for the circuit design of a small PLL that work as frequency synthesizer from 100M to 5GHz 

first circuit is PFD circuit :

<img width="355" height="385" alt="image" src="https://github.com/user-attachments/assets/a741244b-df0d-4e04-9801-6ee7878c18ef" />

PFD circuit :

<img width="1259" height="618" alt="image" src="https://github.com/user-attachments/assets/77d09871-d7e6-4b71-aebe-c3dc9649c82f" />

PFD D_flip_flop :

<img width="1160" height="630" alt="image" src="https://github.com/user-attachments/assets/b4509db6-c99f-4143-bb80-00c85d87fd84" />

there is a challenge in PFD that is the Dead Zone if the pulse is too small to switch open the charge pump so we need to introduce some delay in the reset path of the PFD but that will be done after designing the charge pump itself .

Charge Pump Test Bench:

<img width="1180" height="635" alt="image" src="https://github.com/user-attachments/assets/567eb483-f06c-417a-a718-cb26ed805c96" />
