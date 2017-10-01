# Introduction
## Prerequistes
### Course Prerequistes
* What Prerequistes are required?
* Linux Academy has the following courses:
  * Ansible Quick Start
  * Using Ansible for Configuration Management and Deployments
* Red Hat recommends you have experience working with Ansible to configure systems.

## YAML Refresh/Overview
### A Refresh About YAML
* What is YAML?
* YAML stands for, YAML Ain't Markup Language. This is to distinguish its purpose as data-oriented, rather than document markup.
* YAML format is key=value.
* Ansible doesn't like you using tabs instead of spaces. It doesn't support tabs from a whitespace perspective.
* --- shows the beginning of a configuration file.
* Lists or external content must be identified by a - as shown in the example below:
```
  var_files:
  - conf/copyright.yml
  - conf/webdefaults.yml
```
* Let's see an example of a YAML file that's used by Ansible.
