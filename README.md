
### Users / Groups
Groups:
- engineering
- finance
- support

Users:
- eng01, eng02  -> engineering
- fin01         -> finance
- sup01         -> support
- auditor       -> read-only access across departments via ACL

## Quick start

### 1) Setup
```bash
git clone <your-repo-url>
cd rhcsa-access-control-lab
sudo chmod +x scripts/*.sh
sudo ./scripts/setup.sh
