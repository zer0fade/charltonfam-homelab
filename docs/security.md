# Security

## PKI Infrastructure
- 2-Tier Microsoft CA
  - Offline Root CA (ECC P-521, 10 year)
  - Online Issuing CA
- CRL published: `https://crl.charltonfam.net/pki/`

## VPN Design
- Site-to-site VPN tunnels via UDM Pro Max
- Full LAN-to-LAN routing between sites

## Future Work
- Linux server PKI enrollment
- Home Assistant certificate hardening
