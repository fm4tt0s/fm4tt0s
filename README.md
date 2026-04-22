# Hello there 👋

```bash
docker run --rm fmattos/hello-world
```
  
```python
#!/usr/bin/python
class TechnologyArchitect:
    def __init__(self):
        """who's this guy"""
        self.name            = "Felipe Mattos"
        self.role            = "Technology Architect, Techy, Cyclist, Father"
        self.languages       = ["pt_BR", "en_US"]
        self.location        = "Campinas, Sao Paulo, Brazil"
        self.stack = {
            "cloud":         ["IBM Cloud", "Openshift", "AWS", "Azure", "GCP"],
            "iac":           ["Terraform", "Ansible", "Puppet"],
            "programming":   ["Python", "Javascript", "Typescript", "Shell Script",
                              "Bash/KSH", "PowerShell", "Go", "Node"],
            "os":            ["Linux", "Unix", "Windows"],
            "stack":         ["Docker", "K8S", "DevSecOps", "CyberSec", "KMS", "PKI"],
            "buzz":          ["Hybrid Cloud Architecture", "Cloud Modernization", "SRE",
                              "Observability Design", "Always-on Principles", "Security",
                              "Encryption", "Key Lifecycle Management", "InfraSec",
                              "REST APIs", "Data Pipelines"],
        }

    def __str__(self):
        lines = [
            f"  name:        {self.name}",
            f"  role:        {self.role}",
            f"  languages:   {', '.join(self.languages)}",
            f"  location:    {self.location}",
            "",
            "  stack:",
        ]
        for category, items in self.stack.items():
            lines.append(f"    {category}:")
            for item in items:
                lines.append(f"      - {item}")
        return "\n".join(lines)

    def say_hi(self):
        print("Thanks for stopping by, hope you enjoy some of my work.")

me = TechnologyArchitect()
print(me)
print()
me.say_hi()
```
