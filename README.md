# 🚀 n8n Deployment with Auto SSL (OCI Ubuntu)

## Steps

1. Clone repo:
   ```bash
   git clone https://github.com/YOUR_USERNAME/n8n-docker-setup.git
   cd n8n-docker-setup
   ```

2. Update `.env` with your domain, email, and password.

3. Start services:
   ```bash
   docker-compose up -d
   ```

4. Open in browser:
   ```
   https://www.n8n.jangame.org
   ```

Login with `admin / your-password`.

## Notes
- SSL certs auto-renew via Let's Encrypt companion.
- n8n data stored in `~/.n8n` on your server.
