## Requirements

- Python 3.6+
- PyQt5
- requests

## Installation

1. Clone this repository:

```bash
git clone https://github.com/para911/ipchanger
```

2. Navigate to the project directory:

```bash
cd ipchanger
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

Run the application:

```bash
sudo python ip_changerEN.py
```

Once the application is open:

- **Update Proxy List** — Fetch and verify available proxies.
- **Change IP Once** — Change your IP address manually.
- **Start Automatic IP Change** — Automatically switch proxies based on the selected interval.
- **Stop** — Stop the automatic IP changing process.
- **Reset IP** — Restore the original network/proxy configuration.

## Notes

- Make sure the application has the required permissions to modify system proxy settings.
- An active internet connection is required to fetch and verify proxy servers.
- Some antivirus or security software may interfere with proxy configuration changes.
- Proxy availability and connection quality may vary depending on the proxy provider.

## Platform Support

| Platform | Status |
| --- | --- |
| Windows | Tested on Windows 10 |
| macOS | Tested on macOS Catalina and later |
| Linux | Tested on Ubuntu 20.04 |

Linux users may require additional configuration depending on the desktop environment and network setup.
