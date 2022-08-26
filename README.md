```js
from Github import GithubReadme

class Ishan:
    def __init__(self):
        self.name = "Ishan"
        self.knowas = "Legend"
        self.age = "17"
        self.location = "Bangladesh"
        self.work = "Developer"
        self.system = "Windows 11, x64"

    def skills(self):
        self.languages = {
            "main": ["Python", "Javascript", "Node.js", , "HTML/CSS/JS"],
            "learning": ["djs", "Django"]
        }

        self.works = ['Discord Bots', 'Website', 'Server Manager', 'Community Manager',  'etc...']
    
    def social_media(self):
        self.discord = "@Ishannnn#6266"
        self.instagram = "_ishannnnn12"
  


if __name__ == "__main__":
    readme = GithubReadme.create(Ishan)
```
