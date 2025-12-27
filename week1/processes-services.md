# Processes & Services (Week 1)

## Key commands
- `ps aux`
- `top` / `htop`
- `kill` / `killall`
- `systemctl status <service>`
- `systemctl start|stop|restart <service>`
- `journalctl -xe`

## Troubleshooting checklist
1. Check service status: `systemctl status`
2. Check logs: `journalctl -xe`
3. Verify config path and permissions
4. Restart and re-check

## Mini lab
Pick a service (example: ssh) and write:
- how to check status
- how to restart it
- which logs you would check if it fails
