1. Download Kasm Workspaces and follow the instructions. Use a different port during installation with the -L flag.
2. Go to /opt/kasm/*/docker and change all networks in the compose yaml to the shared nginx one
3. In NPM: foward hostname = kasm_proxy
4. Go to Zones in kasm. upstream auth address = proxy, proxy port = 0
