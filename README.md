## HELLO, XICANO IN THE HUB

<!--
**XICANO88/XICANO88** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

🐧 konaba ha'u: 
```python
class XICANO:
    def __init__(self):
        self.name     = "Xisto Caetano I.G.N.S.da Cunha"
        self.role     = "Network Engineer"
        self.field    = "Faculdade Engenharia Ciencia e Tecnologia"
        self.tools    = "Linux, Cisco ,Wireshark, Metasploit "
        self.focus    = ["Cybersecurity", "ScriptToolkit", "IOT"]
        
        self.skills   = {
                     "Networking" : ["Analysist", "Troubleshooting", "Penetration Testing"],
                     "Script": ["Toolkit", "Cheat Code"],
                     "IOT" : ["Arduino", "Machine Learning"]
         }

    def __repr__(self):
        return (
            f"<{self.__class__.__name__} | "
            f"{self.role} | ">'
        )

me = XICANO()
print(me)
# </XICANO | Network Engineer | "Discipline ≠ Motivation">
