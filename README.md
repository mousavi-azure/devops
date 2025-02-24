# 🚀 Ansible Playbooks Collection  

Welcome to the **Ansible Playbooks Collection**! 🎯 This repository contains practical, well-tested Ansible playbooks to automate server configurations, deployments, and system management.  

## 📂 Available Playbooks  

| Playbook | Description |
|----------|------------|
| [Install Nginx & Certbot](playbooks/install-nginx-certbot.yml) | Installs Nginx and Certbot with SSL auto-configuration |
| [Setup Docker](playbooks/setup-docker.yml) | Installs and configures Docker on the target machine |
| [User Management](playbooks/user-management.yml) | Creates users, sets SSH keys, and manages permissions |
| [System Hardening](playbooks/system-hardening.yml) | Applies security best practices for Linux servers |
| [Update & Upgrade](playbooks/update-upgrade.yml) | Updates system packages and applies security patches |

---

## 🚀 **How to Use**  

### 🔹 Prerequisites  
Ensure you have:  
✅ A control machine with Ansible installed  
✅ SSH access to the target server  
✅ An inventory file specifying the hosts  

### 📌 **Using a Playbook**  
Run the following command to apply a playbook:  
```sh
ansible-playbook -i inventory.ini playbooks/install-nginx-certbot.yml
🛠 Example Inventory File (inventory.ini)
ini
Copy
Edit
[webservers]
192.168.1.10 ansible_user=ubuntu ansible_ssh_private_key_file=~/.ssh/id_rsa
💡 Why Use This Repository?
✔ Production-Ready: These playbooks follow best practices.
✔ Beginner-Friendly: Clear and simple instructions for use.
✔ Time-Saving: Automate tasks and reduce manual setup.

🤝 Contributing
Want to improve or add new playbooks? Feel free to fork this repository and create a pull request! 🚀

📜 License
This project is licensed under the MIT License.
