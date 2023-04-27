# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

STEP04_HARDHAT
Hardhat for Visual Studio Code is the official Hardhat extension that adds advanced support for Solidity to VSCode. 
Stated with following steps of Hardhat_00
 npm install --save-dev hardhat

why install npm ……….  npm install --save-dev hardhat
کمانڈ "npm install --save-dev hardhat" آپ کے پروجیکٹ میں ترقیاتی انحصار کے طور پر Ethereum سمارٹ کنٹریکٹ ڈویلپمنٹ کے لیے Hardhat کے ترقیاتی ماحول کو انسٹال کرنے کے لیے استعمال کیا جاتا ہے۔
Hardhat Ethereum blockchain پر سمارٹ معاہدوں کی تعمیر، جانچ اور تعیناتی کے لیے ایک مقبول اور طاقتور ٹول ہے۔ اس کمانڈ کو استعمال کرتے ہوئے، آپ اپنے پروجیکٹ میں ہاردت کو ترقیاتی انحصار کے طور پر شامل کر رہے ہیں، جس کا مطلب ہے کہ یہ صرف مقامی طور پر انسٹال ہوگا اور ترقی کے عمل کے دوران استعمال ہوگا۔
"--save-dev" جھنڈا npm سے کہتا ہے کہ Hardhat کو آپ کے پروجیکٹ کی "package.json" فائل میں ترقیاتی انحصار کے طور پر شامل کرے، جو آپ کے پروجیکٹ کے لیے انحصار کو منظم کرنے کے لیے استعمال ہوتی ہے۔ اس کا مطلب یہ ہے کہ جب دوسرے ڈویلپرز آپ کے پروجیکٹ پر کام کرتے ہیں، تو وہ اپنی مقامی مشین پر ہاردات سمیت تمام مطلوبہ انحصار کو انسٹال کرنے کے لیے آسانی سے "npm install" چلا سکتے ہیں۔
مجموعی طور پر، اس کمانڈ کے ساتھ Hardhat کو انسٹال کر کے، آپ اپنے Ethereum سمارٹ معاہدوں کی تعمیر اور جانچ کے لیے ایک طاقتور ترقیاتی ماحول قائم کر رہے ہیں۔

npm hardhat

Welcome to Hardhat v2.14.0
    What do you want to do? ...
    Create a JavaScript project
>  Create a TypeScript project
    Create an empty hardhat.config.js
    Quit

√ What do you want to do? · Create a TypeScript project
√ Hardhat project root: · D:\Q2\Assignments\web3\hardhat\hardhat-000-practice
? Do you want to add a .gitignore? (Y/n) » y
You need to install these dependencies to run the sample project:
  npm install --save-dev "hardhat@^2.14.0" "@nomicfoundation/hardhat-toolbox@^2.0.0"
Project created
See the README.md file for some example tasks you can run
Give Hardhat a star on Github if you're enjoying it!
     https://github.com/NomicFoundation/hardhat
npx hardhat
Error HH14: Your Hardhat project uses typescript, but it's not installed.
Please run: 
npm install --save-dev typescript
For more info go to https://hardhat.org/HH14 or run Hardhat with --show-stack-traces
Error HH13: Your Hardhat project uses typescript, but ts-node is not installed.
Please run: npm install --save-dev ts-node
npm install --save-dev ts-node
For more info go to https://hardhat.org/HH13 or run Hardhat with --show-stack-traces
Error: Cannot find module '@nomicfoundation/hardhat-toolbox'
npm install @nomicfoundation/hardhat-toolbox

What is npx hardhat
npx hardhat ایک کمانڈ لائن انٹرفیس (CLI) ٹول ہے جو Ethereum blockchain پر سمارٹ کنٹریکٹس اور ڈی سینٹرلائزڈ ایپلی کیشنز (DApps) کی تعمیر، جانچ اور تعیناتی کے لیے استعمال ہوتا ہے۔ Hardhat Ethereum کے لیے ایک ترقیاتی ماحول ہے جو سمارٹ معاہدوں کو تیار کرنے اور جانچنے کے عمل کو آسان بنانے کے لیے ٹولز کا ایک مجموعہ فراہم کرتا ہے، بشمول ایک مقامی بلاکچین نیٹ ورک، کنٹریکٹ ٹیسٹنگ فریم ورک، اور تعیناتی اسکرپٹس۔

npx hardhat کا استعمال کرتے ہوئے، ڈویلپرز ایک نئے Ethereum پروجیکٹ کو شروع کر سکتے ہیں، اپنے سمارٹ معاہدوں کو مرتب کر سکتے ہیں، ٹیسٹ چلا سکتے ہیں، اور اپنی ایپلیکیشنز کو مقامی یا عوامی Ethereum نیٹ ورک پر تعینات کر سکتے ہیں۔ Hardhat مقبول Ethereum ڈویلپر ٹولز، جیسے Truffle اور Remix کے ساتھ انضمام کی بھی حمایت کرتا ہے، اور موجودہ ترقیاتی ورک فلو میں آسانی سے ضم کیا جا سکتا ہے۔

مجموعی طور پر، npx hardhat Ethereum ڈویلپرز کے لیے ایک طاقتور اور لچکدار ٹول ہے جو انہیں اعلیٰ معیار کے سمارٹ کنٹریکٹس اور DApps کو آسانی کے ساتھ بنانے اور تعینات کرنے کے قابل بناتا ہے۔

npx hardhat
Hardhat version 2.14.0
Usage: hardhat [GLOBAL OPTIONS] <TASK> [TASK OPTIONS]
GLOBAL OPTIONS:
  --config            	A Hardhat config file.
  --emoji               	Use emoji in messages.
  --flamegraph      	Generate a flamegraph of your Hardhat tasks
  --help                	Shows this message, or a task's help if its name is provided
  --max-memory      	The maximum amount of memory that Hardhat can use.
  --network             	The network to connect to.
  --show-stack-traces   Show stack traces (always enabled on CI servers).
  --tsconfig            	A TypeScript config file.
  --typecheck          	Enable TypeScript type-checking of your scripts/tests
  --verbose             	Enables Hardhat verbose logging
  --version             	Shows hardhat's version.
AVAILABLE TASKS:
  check                 	Check whatever you need
  clean                 	Clears the cache and deletes all artifacts
  compile               	Compiles the entire project, building all artifacts
  console               	Opens a hardhat console
  coverage              	Generates a code coverage report for tests
  flatten               	Flattens and prints contracts and their dependencies. If no file is passed, all the contracts in the project will be flattened.
  gas-reporter:merge
  help                  	Prints this message
  node                  	Starts a JSON-RPC server on top of Hardhat Network
  run                   	Runs a user-defined script after compiling the project
  test                  	Runs mocha tests
  typechain             	Generate Typechain typings for compiled contracts
  verify                Verifies contract on Etherscan
To get help for a specific task run: npx hardhat help [task]
npx hardhat test
npx hardhat testایک کمانڈ ہے جو Hardhat پروجیکٹ میں سمارٹ معاہدوں کے لیے ٹیسٹ سوٹ چلاتی ہے۔ Hardhat ایک ٹیسٹنگ فریم ورک فراہم کرتا ہے جو ڈویلپرز کو اپنے معاہدوں کے لیے Solidity یا JavaScript میں ٹیسٹ لکھنے کی اجازت دیتا ہے، اور پھر ان ٹیسٹوں کو مقامی طور پر چلاتا ہے تاکہ یہ یقینی بنایا جا سکے کہ ان کے معاہدے حسب منشا کام کرتے ہیں۔

npx hardhat ٹیسٹ چلانے سے معاہدوں کو مرتب کیا جائے گا اور پھر پروجیکٹ کے ٹیسٹ فولڈر میں تمام ٹیسٹوں کو انجام دیا جائے گا۔ پہلے سے طے شدہ طور پر، Hardhat Mocha کو ٹیسٹنگ فریم ورک کے طور پر اور Chai کو دعویٰ لائبریری کے طور پر استعمال کرتا ہے۔ ڈویلپرز hardhat.config.js فائل میں ترمیم کرکے یا کمانڈ لائن آرگیومینٹس کے طور پر آپشن پاس کر کے ٹیسٹنگ کنفیگریشن کو اپنی مرضی کے مطابق بنا سکتے ہیں۔

npx hardhat ٹیسٹ کا آؤٹ پٹ ہر ٹیسٹ کے نتائج دکھائے گا، بشمول پاس ہونے اور فیل ہونے والے ٹیسٹوں کی تعداد، نیز غلطی کے پیغامات یا ڈیبگ کی معلومات۔ اس سے ڈویلپرز کو اپنے معاہدوں میں مسائل اور کیڑے کی نشاندہی کرنے میں مدد ملتی ہے اور اس کے معیار اور وشوسنییتا کو بہتر بنانے کے لیے اپنے کوڈ پر تیزی سے اعادہ کرتے ہیں۔ مجموعی طور پر، npx hardhat ٹیسٹ Ethereum کے ڈویلپرز کے لیے ایک اہم کمانڈ ہے جو اس بات کو یقینی بنانا چاہتے ہیں کہ ان کے سمارٹ کنٹریکٹس کو لائیو نیٹ ورک پر تعینات کرنے سے پہلے محفوظ اور فعال ہوں۔

Compiled 1 Solidity file successfully
  Lock
    Deployment
      √ Should set the right unlockTime (2577ms)
      √ Should set the right owner
      √ Should receive and store the funds to lock
      √ Should fail if the unlockTime is not in the future (53ms)
    Withdrawals
      Validations
        √ Should revert with the right error if called too soon
        √ Should revert with the right error if called from another account
        √ Shouldn't fail if the unlockTime has arrived and the owner calls it
      Events
        √ Should emit an event on withdrawals (39ms)
      Transfers
        √ Should transfer the funds to the owner
  9 passing (3s)
npx hardhat run scipts/dploy.ts
Lock with 0.001ETH and unlock timestamp 1682243738 deployed to 0x5FbDB2315678afecb367f032d93F642f64180aa3
مجموعی طور پر، npx hardhat run scripts/deploy.ts Ethereum کے ڈویلپرز کے لیے ایک اہم کمانڈ ہے جو TypeScript کا استعمال کرتے ہوئے اپنے سمارٹ کنٹریکٹس کو تیزی سے اور محفوظ طریقے سے نیٹ ورک پر تعینات کرنا چاہتے ہیں۔

npx hardhat node

npx hardhat node ایک کمانڈ ہے جو Hardhat ترقیاتی ماحول کا استعمال کرتے ہوئے ایک مقامی Ethereum نوڈ شروع کرتی ہے۔

Hardhat Ethereum نیٹ ورک پر سمارٹ معاہدوں کی تعمیر اور جانچ کے لیے ایک مقبول ترقیاتی ماحول ہے۔ یہ ٹولز اور خصوصیات کا ایک مجموعہ فراہم کرتا ہے تاکہ ڈویلپرز کے لیے اپنے سمارٹ معاہدوں کو مرکزی ایتھریم نیٹ ورک پر تعینات کرنے سے پہلے مقامی طور پر لکھنا اور ان کی جانچ کرنا آسان بنا سکے۔

npx ایک کمانڈ ہے جو آپ کو Node.js پیکیج کو مقامی طور پر انسٹال کیے بغیر چلانے کی اجازت دیتی ہے۔ لہذا جب آپ npx hardhat node چلاتے ہیں، تو یہ Hardhat پیکیج کو ڈاؤن لوڈ اور چلائے گا اور ایک مقامی Ethereum نوڈ شروع کرے گا جسے آپ ترقی اور جانچ کے لیے استعمال کر سکتے ہیں۔

Hardhat کا استعمال کرتے ہوئے مقامی Ethereum نوڈ کو چلانا سمارٹ معاہدوں کی جانچ کرنے، خودکار ٹیسٹ چلانے، اور Ethereum نیٹ ورک کے ساتھ بات چیت کے لیے حقیقی لین دین کی فیس ادا کیے بغیر یا مین نیٹ ورک پر لین دین کی تصدیق ہونے کا انتظار کرنے کے لیے مفید ہے۔

Started HTTP and WebSocket JSON-RPC server at http://127.0.0.1:8545/
Accounts
========
WARNING: These accounts, and their private keys, are publicly known.     
Any funds sent to them on Mainnet or any other live network WILL BE LOST.
Account #0: 0xf39Fd6e51aad88F6F4ce6aB8827279cffFb92266 (10000 ETH)
Private Key: 0xac0974bec39a17e36ba4a6b4d238ff944bacb478cbed5efcae784d7bf4f2ff80
Account #1: 0x70997970C51812dc3A010C7d01b50e0d17dc79C8 (10000 ETH)
Private Key: 0x59c6995e998f97a5a0044966f0945389dc9e86dae88c7a8412f4603b6b78690d
Account #2: 0x3C44CdDdB6a900fa2b585dd299e03d12FA4293BC (10000 ETH)
Private Key: 0x5de4111afa1a4b94908f83103eb1f1706367c2e68ca870fc3fb9a804cdab365a
Account #3: 0x90F79bf6EB2c4f870365E785982E1f101E93b906 (10000 ETH)
Private Key: 0x7c852118294e51e653712a81e05800f419141751be58f605c371e15141b007a6
Account #4: 0x15d34AAf54267DB7D7c367839AAf71A00a2C6A65 (10000 ETH)
Private Key: 0x47e179ec197488593b187f80a00eb0da91f1b9d0b13f8733639f19c30a34926a
Account #5: 0x9965507D1a55bcC2695C58ba16FB37d819B0A4dc (10000 ETH)
Private Key: 0x8b3a350cf5c34c9194ca85829a2df0ec3153be0318b5e2d3348e872092edffba
Account #6: 0x976EA74026E726554dB657fA54763abd0C3a0aa9 (10000 ETH)
Private Key: 0x92db14e403b83dfe3df233f83dfa3a0d7096f21ca9b0d6d6b8d88b2b4ec1564e
Account #7: 0x14dC79964da2C08b23698B3D3cc7Ca32193d9955 (10000 ETH)
Private Key: 0x4bbbf85ce3377467afe5d46f804f221813b2bb87f24d81f60f1fcdbf7cbf4356
Account #8: 0x23618e81E3f5cdF7f54C3d65f7FBc0aBf5B21E8f (10000 ETH)
Private Key: 0xdbda1821b80551c9d65939329250298aa3472ba22feea921c0cf5d620ea67b97
Account #9: 0xa0Ee7A142d267C1f36714E4a8F75612F20a79720 (10000 ETH)
Private Key: 0x2a871d0798f97d79848a013d4936a73bf4cc922c825d33c1cf7073dff6d409c6
Account #10: 0xBcd4042DE499D14e55001CcbB24a551F3b954096 (10000 ETH)
Private Key: 0xf214f2b2cd398c806f84e317254e0f0b801d0643303237d97a22a48e01628897
Account #11: 0x71bE63f3384f5fb98995898A86B02Fb2426c5788 (10000 ETH)
Private Key: 0x701b615bbdfb9de65240bc28bd21bbc0d996645a3dd57e7b12bc2bdf6f192c82
Account #12: 0xFABB0ac9d68B0B445fB7357272Ff202C5651694a (10000 ETH)
Private Key: 0xa267530f49f8280200edf313ee7af6b827f2a8bce2897751d06a843f644967b1
Account #13: 0x1CBd3b2770909D4e10f157cABC84C7264073C9Ec (10000 ETH)
Private Key: 0x47c99abed3324a2707c28affff1267e45918ec8c3f20b8aa892e8b065d2942dd
Account #14: 0xdF3e18d64BC6A983f673Ab319CCaE4f1a57C7097 (10000 ETH)
Private Key: 0xc526ee95bf44d8fc405a158bb884d9d1238d99f0612e9f33d006bb0789009aaa
Account #15: 0xcd3B766CCDd6AE721141F452C550Ca635964ce71 (10000 ETH)
Private Key: 0x8166f546bab6da521a8369cab06c5d2b9e46670292d85c875ee9ec20e84ffb61
Account #16: 0x2546BcD3c84621e976D8185a91A922aE77ECEc30 (10000 ETH)
Private Key: 0xea6c44ac03bff858b476bba40716402b03e41b8e97e276d1baec7c37d42484a0
Account #17: 0xbDA5747bFD65F08deb54cb465eB87D40e51B197E (10000 ETH)
Private Key: 0x689af8efa8c651a91ad287602527f3af2fe9f6501a7ac4b061667b5a93e037fd
Account #18: 0xdD2FD4581271e230360230F9337D5c0430Bf44C0 (10000 ETH)
Private Key: 0xde9be858da4a475276426320d5e9262ecfc3ba460bfac56360bfa6c4c28b4ee0
Account #19: 0x8626f6940E2eb28930eFb4CeF49B2d1F2C9C1199 (10000 ETH)
Private Key: 0xdf57089febbacf7ba0bc227dafbffa9fc08a93fdc68e1e42411a14efcf23656e
npx hardhat run scripts/deploy.ts --network localhost
Lock with 0.001ETH and unlock timestamp 1682243829 deployed to 0x5FbDB2315678afecb367f032d93F642f64180aa3



