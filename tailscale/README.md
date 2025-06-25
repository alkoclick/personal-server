Activating tailscale ssh on the host:

Install first:
```bash
curl -fsSL https://tailscale.com/install.sh | sh
```
YOLO I guess

Then login:
```bash
sudo tailscale login
```

Then avoid root:
```bash
sudo tailscale set --operator=$USER
```

Then enable SSH:
```bash
tailscale set --ssh
```

Then go to the Tailscale admin console and disable key expiration for this machine!
That's it, we're done!


Oh, and If you ever need to force reauth:
```bash
tailscale up --ssh --force-reauth
```