# Ansible role '<role>'

An Ansible role for setting up some common utilities:
- sudo
- glances
- alsa/pulseaudio
- fuse
- nfs
- mptfs (Arch/Mint/Ubuntu)
- htop
- dns utilities (dnsutils/bind-utils)

## Requirements
Minimum requirements:
- Arch Linux
- CentOS 7
- Linux Mint 18
- RHEL 7
- Ubuntu 16.10

## Role Variables
| Variable                       | Default                          | Comments (type)  
                                              |
| :---                           | :---                             | :---                                                                                                             |
| sudo_wheel_all                 | pass | Allows members of group wheel to execute any command (pass/nopass/off) |

## Dependencies
No dependencies

## Example Playbook
```Yaml
- hosts: foo
  roles:
  - role: common
```
## Testing

## License

BSD

## Contributors

Issues, feature requests, ideas, suggestions, etc. are appreciated and can be posted in the Issues section. Pull requests are also very welcome. Please create a topic branch for your proposed changes, it's the easiest way to merge back into the project.

- [Oscar Petersson](https://giithub.com/oscpe262/) (Maintainer)
