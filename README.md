# SimpleTCPProxy
A very simple TCP/HTTP proxy copied from http://voorloopnul.com/blog/a-python-proxy-in-less-than-100-lines-of-code/

## Usage
1. Update `forward_to = ('172.16.38.191', 12345)` with the server IP and port with your desired target address
2. Update `listen_to = ('localhost', 12345)` with the port that the proxy would accept connection. Use `0.0.0.0` if you want it to accept external request.
3. `python proxy.py`
4. Setup your browser's proxy, or simply browse/telnet to the proxy. All request would forward to `forward_to` and respond would direct back to you.

