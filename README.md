# Stork Verify BOT
Stork Verify BOT

- Register Here : [Stork Verify](https://chrome.google.com/webstore/detail/stork/knnliglhgkmlblppdejchidfihjnockl)
- Use Code: CI14P1PBJB

## Features

  - Auto Get Account Information
  - Auto Run With [Monosans](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/all.txt) Proxy - Choose 1
  - Auto Run With Private Proxy - Choose 2
  - Auto Run Without Proxy - Choose 3
  - Auto Reporting Messages
  - Multi Accounts With Threads

## Requiremnets

- Make sure you have Python3.9 or higher installed and pip.

## Instalation

1. **Clone The Repositories:**
   ```bash
   git clone https://github.com/Not-D4rkCipherX/Stork.git
   ```
   ```bash
   cd Stork
   ```

2. **Install Requirements:**
   ```bash
   pip install -r requirements.txt #or pip3 install -r requirements.txt
   ```

## Configuration

### How to get Refresh Token
<div style="text-align: center;">
  <h4><strong>Refresh Token</strong></h4>
  <img src="image.png" alt="Image" width="500"/>
</div>

## Accounts Setup
```bash
nano tokens.txt
```
- ** Make sure `tokens.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
  your_refresh_token_1
  your_refresh_token_2
  ```
## Proxy (Optional)
```bash
nano proxy.txt
```
- **  Make sure `proxy.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
  ip:port # Default Protcol HTTP.
  protocol://ip:port
  protocol://user:pass@ip:port
  ```

## Run

```bash
python bot.py #or python3 bot.py
```

