# WG-Easy (Wireguard + Web UI) on Elestio with CI/CD

<a href="https://dash.elest.io/deploy?source=cicd&social=dockerCompose&url=https://github.com/elestio-examples/wg-easy"><img src="deploy-on-elestio.png" alt="Deploy on Elest.io" width="180px" /></a>

Example CI/CD pipeline showing how to deploy a WG-Easy instance to elestio.

# Once deployed ...

You are able now to connect to the WEB UI:

    https://[CI_CD_DOMAIN]
    Password: [SOFTWARE_PASSWORD] (set in env vars)

Once connected, you can create a new client and scan the QR code from your phone, or download the configuration file for your desktop. 
