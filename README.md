# Hello there 👋

```bash
docker run --rm fmattos/hello-world
```
  
```python
#!/usr/bin/python

class TechnologyArchitect:

    def __init__(self):
        """who's this guy"""
        self.name = "Felipe Mattos"
        self.role = "Technology Architect, Cyclist, Techy, Father"
        self.language_spoken = ["pt_BR", "en_US"]

    def say_hi(self):
        """just saying"""
        print("Thanks for stopping by, hope you enjoy some of my work.")

me = TechnologyArchitect()
me.say_hi()
```

## Stack

```python
#!/usr/bin/python

data = [
    ['cloud', 'IBM Cloud', 'Openshift', 'AWS', 'Azure', 'GCP'],
    ['iac', 'Terraform', 'Ansible', 'Puppet'],
    ['programming', 'Python', 'Javascript', 'Typescript', 'Shell Script', 'Bash/KSH',
    'PowerShell', 'Go', 'Node'],
    ['os', 'Linux', 'Unix', 'Windows'],
    ['stack', 'Docker', 'K8S', 'DevSecOps', 'CyberSec', 'KMS', 'PKI'],
    ['buzz', 'Hybrid Cloud Architecture', 'Cloud Modernization', 'SRE', 'Observability Design',
    'Always-on Principles', 'Security', 'Encryption', 'Key Lifecycle Management',
    'InfraSec', 'REST APIs', 'Data Pipelines']
]

for row in data:
    category = row[0]
    items = row[1:]
    print(f"{category}: {', '.join(items)}")
```
