# Westering Playtest

Install once. Open the Westering Playtest shortcut before each session to get updates. Choose Play to host or Join Server to connect.

[Download the Windows installer](https://github.com/rrweidaw-sketch/Westering-Playtest/releases/latest/download/WesteringPlaytest-win-Setup.exe)

No GitHub account, Unity installation or VPN app is needed. This is an early Windows 64-bit prototype. The installer is not code-signed yet, so Windows may show an unknown-publisher warning.

## Join a friend

1. Install Westering Playtest and open its shortcut.
2. Wait for updates to finish.
3. Ask the host for their public address or hostname, port and password.
4. Enter those details in the launcher and click Join Server. The default port is 7770.
5. The address and port are remembered. Enter the password each session.
6. Use the First test guide button for the full test checklist.

Only the host sets up router forwarding and Windows Firewall. Guests do not need to change router settings. The host forwards UDP port 7770 to their hosting PC and shares their public IPv4 address. The hosting connection needs a public IPv4 address that allows inbound connections; carrier-grade NAT may require help from the internet provider.

Close the game before updating. Saves and player identity are stored outside the install folder. If an update fails, retry later or play the installed build.

This repository distributes installers and compiled game updates. The development repository is separate.