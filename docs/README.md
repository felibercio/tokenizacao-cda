# CDA Token Pilot

Este projeto é um piloto para a tokenização de Certificados de Depósito Agropecuário (CDA/WA) utilizando blockchain, com foco em segurança, compliance e integração com oráculos de preço e mercado secundário.

## Objetivo
Tokenizar ativos do agronegócio (CDA/WA), permitindo:
- Registro digital e rastreável dos títulos
- Emissão de tokens lastreados em grãos
- Integração com oráculos de preço (ex: B3)
- Liquidez via mercado secundário (ex: Liqi)
- Compliance e controles de acesso

## Arquitetura Básica
- **CDAToken.sol**: Contrato principal ERC20 customizado para emissão e controle dos tokens lastreados em CDA/WA
- **PriceOracle.sol**: Contrato para atualização e consulta de preços de commodities
- **Testes**: Scripts de teste automatizados para validação dos contratos
- **Scripts**: Scripts de deploy e automação

## Estrutura de Pastas
```
contracts/         # Smart contracts principais
  CDAToken.sol     # Tokenização do CDA/WA
  PriceOracle.sol  # Oráculo de preços

test/              # Testes automatizados
scripts/           # Scripts de deploy

docs/              # Documentação do projeto
```

## Próximos Passos
1. Implementar o contrato CDAToken com funções de registro e tokenização de CDA
2. Implementar o contrato PriceOracle para atualização de preços
3. Desenvolver e rodar testes unitários
4. Realizar deploy na testnet (Polygon Mumbai)
5. Integrar com sistemas externos (CERC, Liqi, oráculos)

---

Para dúvidas ou contribuições, entre em contato com o time de desenvolvimento. 