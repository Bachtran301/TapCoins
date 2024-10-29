
![tap](https://github.com/user-attachments/assets/0fcfa29f-ce6a-4068-a8b4-9bb0f5efb977)

✔️ Auto tap

✔️ Auto task

✔️ Auto upgrade card


# 🛠️ Instructions:

## REQUIREMENTS: NODEJS MUST BE INSTALLED

Run the following command to install the necessary modules:

`npm install`

Create two files: [data.txt](data.txt) and [proxy.txt](proxy.txt)

For those using multiple accounts, it's recommended to use a proxy (if using only one account, there's no need to create the proxy.txt file).

# Proxy format:

http://user:pass@ip:port

# Get data:

In the data.txt file, you need to have the following format:

query_id=xxx or user=xxxx

![Capture](https://github.com/user-attachments/assets/6db0b3ed-86fe-4cf7-b9c3-9dde4c0f2efb)

# Configuration option in config.json

```js
{
    "max_upgrade_cost": 5000,
    "upgrade_delay": 5000
}
```

# Run the tool using the command:

noproxy:

`node tapcoin.js`

proxy:

`node tapcoin-proxy.js`
