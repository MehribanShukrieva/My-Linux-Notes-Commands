
# System & User Management

```bash
# Create a new user
sudo adduser testuser

# Add user to sudo group
sudo usermod -aG sudo testuser

# Show running processes
ps aux

# Kill a process by PID
kill -9 <PID>

# Manage system services
sudo systemctl start nginx
sudo systemctl status nginx
sudo systemctl enable nginx
