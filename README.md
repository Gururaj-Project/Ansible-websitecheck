🌐🔒 Ansible Website & SSL Health Checker ✅

A simple Ansible playbook to:

- 🔎 **Check reachability** of each website/host listed in `hosts.ini`
- 📜 **Inspect SSL/TLS certificates** on each host
- ⏳ **Report certificate expiry days** along with reachability status
- 📡 **Send the results to a configured webhook** (Slack, Teams, etc.)

---

🚀 Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/<your-repo>.git
   cd <your-repo>
2. Update hosts.ini
   Add the websites you want to check.
  
3. Update group_vars/all.yml

4. Add your webhook URL.

5. Run the playbook

bash
Copy code
ansible-playbook -i hosts.ini website.yaml
