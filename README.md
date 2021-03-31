Free tempoary VPS from Github (Windows Server 2019, 2x2.6 Ghz, 7GB ram, 250GB SSD)

1. reg [Ngrok](https://ngrok.com/)
2. fork repo
3. add `NGROK_AUTH_TOKEN` to repo settings > secrets. take from [here](https://dashboard.ngrok.com/get-started/your-authtoken)
4. add your rdp `PASS` to repo settings > secrets.
5. go Actions -> CI and Run workflow
6. open task and take RDP ip and creds

_Maximum VM time:6h_ - Limit from Github for free accounts
