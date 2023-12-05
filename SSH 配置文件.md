配置路径: ~/.ssh/config

```bash
Host fuzhou
    HostName 20.23.11.13
    User zhanjiahan465
    Port 22
    HostKeyAlgorithms +ssh-rsa

Host beijing
    HostName 10.100.2.10
    User zhanjiahan465
    Port 22
    HostKeyAlgorithms +ssh-rsa

Host tgs
    HostName 20.22.7.15
    User zhanjiahan465
    Port 22
    HostKeyAlgorithms +ssh-rsa

Host bastion
    HostName 10.10.99.146
    User zhanjiahan465
    Port 2222
    HostKeyAlgorithms +ssh-rsa
```