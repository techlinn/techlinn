## What is the worst that could happen in `__init__()`?
```python
class Tech:
    def __init__(self):
        self.username = "Tech"
        self.age      = 19
        self.location = "Stockholm, Sweden"
        self.website  = "https://txchnology.cc"
        self.project  = "https://stormss.cc"
        self.contact  = "tech@stormss.cc"

    def info(self):
        return {
            "Username": self.username,
            "Age":      self.age,
            "Location": self.location,
            "Website":  self.website,
            "Project":  self.project,
            "Contact":  self.contact
        }
```
