# Akun.yaml
proxies:
  - name: Ddaniel_trojan_ws
    server: 104.26.6.171
    port: 443
    type: trojan
    password: f0fcd2e4-65c6-4794-95f0-d56933460d14
    skip-cert-verify: true
    sni: sg01.iptr.xyz
    network: ws
    ws-opts:
      path: trojan-ws
      headers:
        Host: sg01.iptr.xyz
    udp: true
