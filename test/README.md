# <h3> Unit tests
  
  The unit tests serve the purpose of proving the above features and the security of Cygnus. 
  
  To run the tests on your local machine, first **make sure to fork Avalanche C-Chain** as all tests are done on the LP token Joe/AVAX from Traderjoe. We use the router to perform the tests also. The reason we did the tests this way was to replicate the dapp as close to real conditions as possible. 

To fork the C-Chain, you can follow hardhat instructions (https://hardhat.org/hardhat-network/guides/mainnet-forking.html). After you can run all our tests in succession with `npx hardhat test`
  
**Borrow contracts control and depositing DAI:**
  
  ![unit1](https://user-images.githubusercontent.com/97303883/175661829-02299e20-a57c-4fa1-8fe0-0b7591c3e5d2.png)

**Collateral contracts control and depositing LP Token:**
  
  ![unit4](https://user-images.githubusercontent.com/97303883/175661964-3706f7f6-75f6-42e5-b975-445881710d84.png)

**Borrow DAI:**
  
  ![unit3](https://user-images.githubusercontent.com/97303883/175661986-707b6b0b-bf24-4701-b7f2-933a6c27e285.png)

**Liquidations and Auto-compounding masterchef rewards:**

  ![unit2](https://user-images.githubusercontent.com/97303883/175662011-98bcef0b-2c38-44c0-ba90-6dcc2e9eae27.png)
