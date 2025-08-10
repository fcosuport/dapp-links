# 🚀 Meu Projeto Web3

[![Solidity](https://img.shields.io/badge/Solidity-%5E0.8.0-363636?style=flat-square&logo=solidity)](https://soliditylang.org/)
[![Next.js](https://img.shields.io/badge/Next.js-13+-000000?style=flat-square&logo=next.js)](https://nextjs.org/)
[![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=flat-square&logo=ethereum)](https://ethereum.org/)
[![Web3](https://img.shields.io/badge/Web3-F16822?style=flat-square&logo=web3.js)](https://web3js.readthedocs.io/)

> Um projeto Web3 completo com smart contracts em Solidity e frontend em Next.js

## 📋 Sobre o Projeto

Dapp para criaçao e compra de liks/urls curtos

## 🏗️ Arquitetura

- **Smart Contracts**: Desenvolvidos em Solidity
- **Frontend**: Next.js com React
- **Blockchain**: Ethereum (BNB Chain)
- **Web3 Library**: web3.js

## 📁 Estrutura do Projeto

```
├── dapp-linkshield/           # Aplicação Next.js
├── smart-contracts/    # Smart contracts Solidity
└── README.md
```

## 🛠️ Tecnologias

### Smart Contracts
- Solidity ^0.8.0
- Remix IDE

### Frontend
- Next.js
- React
- web3.js

### 1. Smart Contracts

Os contratos foram desenvolvidos no Remix IDE. Para usar:

1. Abra o [Remix IDE](https://remix.ethereum.org/)
2. Importe o arquivo `smart-contracts/MeuContrato.sol`
3. Compile e faça o deploy na rede desejada

### 2. Frontend

```bash
cd dapp-linkshield
npm install
npm run dev
```

## 📝 Deploy

### Smart Contract
1. Use o Remix IDE para fazer deploy
2. Copie o endereço do contrato deployado
3. Configure no frontend as variáveis de ambiente

### Frontend
1. Configure as variáveis de ambiente
2. Execute: `npm run build && npm run start`

## 🔗 Links Importantes

- [Documentação do Solidity](https://docs.soliditylang.org/)
- [Next.js Documentation](https://nextjs.org/docs)
- [Ethers.js Documentation](https://docs.ethers.io/)

## 📄 Licença

MIT License

## 🤝 Contribuindo

Pull requests são bem-vindos!