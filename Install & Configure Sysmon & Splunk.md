# Configure network setting on Ubuntu Server

### The command is typically used to configure or troubleshoot network settings on Linux distributions that use Netplan, such as Ubuntu. Defines network settings, such as IP addresses, DNS servers, and routes, in a YAML format.
```bash
sudo nano /etc/netplan/50-cloud-init.yaml
```
![image](https://github.com/user-attachments/assets/e7ccde4c-793b-4ef5-81fd-422a4e941a86)

![image](https://github.com/user-attachments/assets/b717cf60-66b3-47a6-af39-f61cc9e7dd80)

---

### Now, we modify settings as needed and saved.
![image](https://github.com/user-attachments/assets/194c7fac-1341-41da-b031-d726e3a17158)
```bash
sudo netplan apply | for command activate
```
### We modified IP Address.
![image](https://github.com/user-attachments/assets/6e55aaa9-8a41-4405-8ad3-0cc26414a63a)

---

