```python
from github.profile import ReadMe
class ilsyaa ( ReadMe ) :
    def __init__ ( self ) :
        self.username  = "ilsyaa"
        self.location  = "Indonesia"
        self.discord   = "@ilsyaa"
        self.languages = [ "PHP", "Kotlin", "Javascript", "C#", "Java" ]
    def about ( self ) :
        print( f"Hi, I'm {self.username}. Contact me at {self.discord}" )
me = ilsyaa()
me.about()
```
