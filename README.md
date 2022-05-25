⛔️⛔️⛔️ This is RSA implementation is compromised. Do NOT use is for anything else than demonstration purposes 
# Kelptographic SETUP attack on python RSA

This project shows an attack asymmetric kleptogrpahic attack on the RSA algorithmen. The project is based on the [python-rsa](https://github.com/sybrenstuvel/python-rsa) package from Sybren A. Stüvel. It is done by appending code to the key.py file.

This project was carried out as part of a student research project by Yannic Hemmer at the DHBW Karlsruhe. It is intended to show exemplarily how kleptogrpahic attacks work. 
The student research project and a more detailed documentation of the procedure can be found in the main repository of the student research project. It also explains the basics on which the attack is based.
[RSA_Kleptography_Studienarbeit](https://github.com/MeNoSmartBrain/RSA_Kleptography_Studienarbeit)
It also contains the code to extract the private prime factors from the public modulus of a key generated by this repository.

The createCerts.py contains examples for private key for an attacker. I would advice against using them outside this project.

__This repsoitory is for demonstration purposes only. Do NOT use it for generation RSA keypairs for real world use.__

For installation, clone the repository and install it with pip in development mode:
```
python3 -e pip install ./
```

I advice doinng this in a virtual enviroment, which shall be deleted afterwards.

Thanks to Sybren A. Stüvel for letting me use this project and disgussing its stucture with me.

Do not use this for anything other than research
