<pre align="center">
.__.__                                
|__|  |   _________.__._____  _____   
|  |  |  /  ___<   |  |\__  \ \__  \  
|  |  |__\___ \ \___  | / __ \_/ __ \_
|__|____/____  >/ ____|(____  (____  /
             \/ \/          \/     \/ 
</pre> 

```python
from github.profile import ReadMe
class ilsyaa ( ReadMe ) :
    def __init__ ( self ) :
        self.username  = "ilsyaa"
        self.location  = "Indonesia"
        self.discord   = "Ilsyaa#0557"
        self.languages = [ "PHP", "Kotlin", "Javascript", "C#", "Java" ]
    def about ( self ) :
        print( f"Hi, I'm {self.username}. Contact me at {self.discord}" )
me = ilsyaa()
me.about()
```
