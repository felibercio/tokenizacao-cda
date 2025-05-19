# CDA Token Pilot

Este projeto implementa um piloto para tokenização de Certificados de Depósito Agropecuário (CDA/WA) utilizando blockchain, especificamente na rede Polygon (Mumbai Testnet).

## 🚀 Funcionalidades

- Tokenização de CDAs em NFTs (ERC-721)
- Representação digital de certificados agrícolas
- Rastreabilidade e transparência das operações
- Integração com contratos inteligentes para gestão de ativos

## 📋 Pré-requisitos

- Node.js (v16 ou superior)
- npm ou yarn
- MetaMask ou outra wallet compatível com EVM
- Conta na rede Mumbai (Polygon Testnet)

## 🔧 Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/cda-token-pilot.git
cd cda-token-pilot
```

2. Instale as dependências:
```bash
npm install
```

3. Configure as variáveis de ambiente:
- Copie o arquivo `docs/.env.example` para `.env`
- Preencha as variáveis necessárias (RPC URL, chave privada, etc.)

## 🛠️ Desenvolvimento

1. Compile os contratos:
```bash
npm run compile
```

2. Execute os testes:
```bash
npm test
```

3. Faça deploy na rede Mumbai:
```bash
npm run deploy:testnet
```

## 📝 Scripts Disponíveis

- `npm run compile`: Compila os contratos
- `npm test`: Executa os testes
- `npm run deploy:testnet`: Faz deploy na rede Mumbai
- `npm run lint`: Executa o linter nos contratos
- `npm run format`: Formata os arquivos de contrato

## 📚 Documentação

A documentação detalhada do projeto está disponível na pasta `docs/`:

- [Arquitetura](docs/architecture.md)
- [Contratos](docs/contracts.md)
- [Guia de Desenvolvimento](docs/development.md)
- [Guia de Deploy](docs/deployment.md)

## 🤝 Contribuindo

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## ⚠️ Aviso

Este é um projeto piloto e não deve ser usado em produção sem uma auditoria de segurança adequada e aprovação regulatória.

## 📞 Suporte

Para suporte, abra uma issue no GitHub ou entre em contato através do email: seu-email@exemplo.com 