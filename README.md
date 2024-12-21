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

  // SolNode - your solana rpc node, recommend to use Helius paid node
  
  // SolStrmNode - your solana rpc streaming node, recommend to use Helius paid node 
  
  // Jito - enable or disable Jito bundler
  // 10 means Jito bundler tips is 10 * 1000 lamports for each transaction
  // 0 means disable Jito bundler

  // JitoNode - location of Jito node (MAINNET/AMSTERDAM/FRANKFURT/NEWYORK/TOKYO)

