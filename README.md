# solbot
A dotnet based solana bot on pumpfun and raydium 

![image](https://github.com/user-attachments/assets/123efd56-c3ad-4919-a705-b11b90be80ed)

Basic Features:
- Create wallets
- Distribute/Recover tokens
- Query balance

PumpFun Features:
- Launch and Buy () 
- Generate vanity "*pump" address

Common (PumpFun/Raydium) Features:
- BT: a batch trade bot 
- CT: a conditional trade bot
- TT: a TWAP trade bot
- RT: a simple market maker bot
- MM: a sophisticated market maker bot

Global Configurations (in .config):

  <add key="SolNode" value="https://mainnet.helius-rpc.com/?api-key=139cbee9-0de3-4f09-ac5e-99b2055126ea" />
  // SolNode - your solana rpc node, recommend to use Helius paid node
  
  <add key="SolStrmNode" value="wss://mainnet.helius-rpc.com/?api-key=139cdee9-0de3-4f09-ac5e-99b2055126ea" />
  // SolStrmNode - your solana rpc streaming node, recommend to use Helius paid node 
  
  <add key="Jito" value="10" />
  // Jito - enable or disable Jito bundler
  // 10 means Jito bundler tips is 10 * 1000 lamports for each transaction
  // 0 means disable Jito bundler

  <add key="JitoNode" value="TOKYO" />
  // JitoNode - location of Jito node (MAINNET/AMSTERDAM/FRANKFURT/NEWYORK/TOKYO)

