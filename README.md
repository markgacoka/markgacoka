### Hi! I'm Mark Gacoka

[![Twitter Follow](https://img.shields.io/twitter/follow/markgacoka.svg?style=social)](https://twitter.com/markgacoka)  
[![Open Source](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://opensource.org/)

```python
class Profile:
  def __init__(self, name, age, languages):
    self.name = name
    self.age = age
    self.languages = languages
    
  def __repr__(self):
      return "Gacoka's Introduction!"
    
  def __str__(self):
      return ("Name: {} \nAge: {} \nLanguages: {}".format(self.name, self.age, self.languages))
    
  def introduction(self):
    return ("Hello there! Nice to see you. Let's collaborate.")
    
    
if __name__=='__main__':
  gacoka = Profile("Mark Gacoka", 20, ["Python", "Bash", "Javascript"])
  print(gacoka)
  print(gacoka.introduction())

```

:email: markgacoka@gmail.com
:school: Minerva Schools at KGI
