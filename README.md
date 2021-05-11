# how-to-install-vnc-on-windows-server
how to install vnc on windows server

## Step 0: dùng remote desktop kết nối vào server
## Step 1: Download tightvnc cho server, cài đặt và open port 5900, đặt password cho nó
https://www.configserverfirewall.com/windows-10/install-vnc-server-windows-10/
https://tightvnc.com/download.php

Cơ bản nó giống như cài trên ubuntu, cũng phải trải qua các bước là open port, allow firewall cho port đó và đặt password cho vnc. Khác biệt là ô này làm bằng giao diện
## Step 2: Vào laptop của bạn
Cài VNC viewer, sau đó kết nối vào, mở khóa màn hình. Từ đó về sau mỗi khi vào hãy dùng vnc, tắt vnc đi nó không khóa lại màn hình của vps
