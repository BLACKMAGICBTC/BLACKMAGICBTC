- 👋 Hi, I’m @BLACKMAGICBTC
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
BLACKMAGICBTC/BLACKMAGICBTC is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

Hello World 
npm install web3 @portis/web3

import Portis from '@portis/web3';
import Web3 from 'web3';

const portis = new Portis('adc8d491-ac33-4ece-adb6-ca118ac7acdf', 'mainnet');
const web3 = new Web3(portis.provider);
