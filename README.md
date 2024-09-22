### Hello. (•◡•)/

```python
from Kristopher import information

class AboutMe:
    def __init__(self):
        self.name = 'Kristopher'
        self.nick = 'lord3nd3r'
        self.birthday = 19800305
        self.gender = 'male'
        self.about = 'full stack developer/sysadmin that enjoys breaking and fixing things.'
        self.location = 'Florida'
        self.hobbies = ['Programming', 'Sysadmin', 'IRC', 'LLM']
        self.languages = ['Python',  'JavaScript', 'Go', 'Tcl', 'C', 'C++']
        self.os = ['Ubuntu', 'FreeBSD', 'Fedora']
        self.timezone = ['UTC-6']
        self.projects = [
            {
                'project': 'moobot',
                'language': 'Python',
                'description': "This is a Python-based script for sopel."
            },
        ]

    def introduce(self):
        print(f'Hello, my name is {self.name}. I\'m from {self.location} and am {self.age} years old.')
        print(f'I\'m a {self.about}.')

my_profile = AboutMe()
my_profile.introduce()
