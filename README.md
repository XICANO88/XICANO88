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

🐧 About Me : 
```python
class XICANO:
    def __init__(self):
        self.name     = "Xisto Caetano I.G.N.S.da Cunha"
        self.role     = "Network Engineer"
        self.field    = "Universidade Nacional Timor Lorosa'e"
        self.tools    = "Linux","Cisco","Wireshark","Metasploit"
        self.focus    = ["Cybersecurity", "ScriptToolkit", "IOT"]
        
        self.skills   = {
                     "Networking" : ["Analysis", "Troubleshooting", "Penetration Testing"],
                     "Script": ["Bug Bounty", "Cheat Code"],
                     "IOT" : ["Arduino", "Machine Learning"]
         }

    def __repr__(self):
        return (
            f"<{self.__class__.__name__} | "
            f"{self.role} | "
            f'"{self.motto}">'
        )

me = XICANO()
print(me)
# </XICANO | Network Engineer | "Build. Debbugin. Repeat.">
