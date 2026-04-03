# Hello there 👋
  
```python
#!/usr/bin/python

class TechnologyArchitect:

    def __init__(self):
        """who's this guy"""
        self.name = "Felipe Mattos"
        self.role = "Technology Architect"
        self.language_spoken = ["pt_BR", "en_US"]

    def say_hi(self):
        """just saying"""
        print("Thanks for stopping by, hope you enjoy some of my work.")

me = TechnologyArchitect()
me.say_hi()
```

## Technologies & Tools

```python
tech_stack = {
    'cloud': ['IBM Cloud', 'Openshift', 'AWS', 'Azure', 'GCP'],
    'iac': ['Terraform', 'Ansible', 'Puppet'],
    'programming': ['Python', 'Javascript', 'Typescript', 'Shell Script', 'Bash/KSH', 'PowerShell', 'Go']
}

for category, items in tech_stack.items():
    print(f"{category}: {', '.join(items)}")
```
