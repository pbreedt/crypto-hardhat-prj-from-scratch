## commands

```sh
npm init
npm install --save-dev hardhat
npx hardhat init # selected TypeScript, rest default
# above creates:
# .
# ├── contracts
# │   └── Lock.sol
# ├── ignition
# ├── test          
# │   └── Lock.ts    
# ├── hardhat.config.ts
# └── tsconfig.json
npx hardhat test
```