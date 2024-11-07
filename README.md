# NodePay Multi Account 100% Uptime FREE Python Bot [v2] Bot

This Python Bot script manages WebSocket connections through specified HTTP proxies, Unlimited Proxies and multiple Nodepay Accounts handling authentication and maintaining persistent connections with a server. The script also includes functionality to periodically send ping messages to keep the connection alive forever. If you can run your pc 24/7 then you dont need a Vps or proxy server lol.

## Features

- Connects to a WebSocket server using HTTP proxies.
- Handles Multiple Nodepay User IDs at once !! Multiple Proxies (1 Proxy ~60 $NODEPAY)
- Per Proxy ~1400 ** $NODEPAY per day** Unlimited proxies Make Unlimited Money !
- Handles All kinds of Error such a Dead proxy/ SSL: WRONG_VERSION_NUMBER / sent 1011 (internal error) keepalive ping timeout; no close frame received / 500 Internal Server Error / sent 1011 (internal error) keepalive.
- Automatically removes the dead proxy from the File!!

#Get NP_TOKEN

1. Open the link and log in [https://app.nodepay.ai/dashboard](https://app.nodepay.ai/dashboard)
2. Press F12 on the page to open the console and enter the code (Ctrl + Shift + i) inspect
3. Write `localStorage.getItem('np_token');` in the console
4. "PRINTED TEXT IS THE Np _TOKEN"
5. ![image](https://github.com/Solana0x/nodepay/assets/142747768/bf907faa-0e56-4935-a5dc-da95f612fa07)

#Get USer_Id (NOT NEEDED IN NEW CODE) 

1. Press F12 on the page to open the console and enter the code (Ctrl + Shift + i) inspect
2. Go To Networks Tab in the Inspect
3. Search for the Devices then check the response
4. You will Get the User-id there
5. ![image](https://github.com/Solana0x/nodepay/assets/142747768/d9b07511-0554-4330-8d7c-81395b92c25b)

#Get Proxies IP address HTTP

1. Create a Account in  [https://www.webshare.io/?referral_code=gppl5h10bwn5](https://www.webshare.io/)
2. For webshare plan are 1000 Proxy for 1 Month !! hence total earning is => 43,200,000 $NODEPAY Points
3. ![image](https://github.com/Solana0x/nodepay/assets/142747768/82eb59b5-9f74-4d14-96b0-c35bb1e8925e)
4. You Got 1000 Ips now => Earning == ~1,440,000 Tokens per day and distribute Ips across multiple accounts / User ID !! You get 250GB bandwidth so create 20-30 Nodepay accounts to get 25-30M nodepay points per day
5. USe only webshare to Buy proxy because as of now only webshare website opened port for nodepay ! other proxy sellers i dont know !

## Requirements

- Invitation link Nodepay Accounts ( [https://app.nodepay.ai](https://app.nodepay.ai/register?ref=ZUCBuJaIoBXLE6J) )
- Python (install Python By - https://www.python.org/downloads/ [windows/mac]) or Ubuntu Server [`sudo apt install python3`]
- VPS Server ! You can get Via AWS free Tier or Google Free tier or Gitpod or any online for just ~ 2-5$ per month
- Proxy Server - you can buy DataCenter Proxies to Earn $NODEPAY Some Free Cheap proxies (Best proxy providers is webshare)
- Get NP_token andcUser ID from Nodepay Dashboard

## SETPS TO RUN THE CODE -

Before running the script, ensure you have Python installed on your machine. Then, install the necessary Python packages using:

1. ``` git clone https://github.com/Solana0x/nodepay.git ```
2. ``` cd nodepay ```
3. ``` pip install -r requirements.txt ```
4. Replace `NP TOken` list in correct formate in `node.py` File Line ```9```.
5. By default 100 proxies will be taken randomly if you wana change then change here `active_proxies = [proxy for proxy in all_proxies[:100] if is_valid_proxy(proxy)]` line 169. Here 100 means 100 proxy will be used at once.
6. Dont Forget to add multiple proxies in the proxy.txt file you can add 1000+ proxy !! Formate # `HTTP://username:pass@ip:port`.
7. You can get Multiple Proxy Ip address from Proxies.fo Website !! [use multiple IP ! `1 IP == ~1400 $NODEPAY per Day `.
8. To Run Script `python3 node.py` - Proxy one
10. To Run multiple User ID just copy paste the `node.py` file code and create new python file and repeat the process !!. 

**Note** - 1 ip == 1000-1400 $Nodepay Per Day.

![image](https://github.com/Solana0x/nodepay/assets/142747768/cbfd5d20-6d30-494c-9af1-34c2415d27d1)

## FOR ANY KIND OF HELP CONTACT : ` 0xphatom ` on Discord  https://discord.com/users/979641024215416842
