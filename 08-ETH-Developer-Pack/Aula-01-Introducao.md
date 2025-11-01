# Aula 1 - Introdução a Ethereum

[Vídeo da Aula 1](https://www.youtube.com/live/k1XBYRjzEhw?si=eb-3fFrfnaFkKuS-)

<!-- https://pad.riseup.net/p/edp-pt-01 -->
<!-- Apresentação: https://docs.google.com/presentation/d/e/2PACX-1vRusC1VTRk8lxgZC_mtrDUxtKeMuLskpIElmmrxUYBDJIV8oFWzXZNQpwybMFMZg_9iWSHEI-GTiNTZ/pub?start=false&loop=false&delayms=3000&slide=id.g387646358f0_0_2 -->


Instrutora: Solange Gueiros (Sol)

---
## Blockchain

- blockchain = cadeia de blocos
- bloco: hash
- consenso -> imutabilidade
- transações e máquina de estados

--- 

## Ethereum
- blockchain/infraestrutura
- criado em 2013 por Vitalik Buterin
- 1º bloco: 30 de julho de 2015
- contratos inteligentes (smart contracts)
- aplicativos distribuídos (dApps), descentralizados
- máquina virtual "Ethereum Virtual Machine" (EVM) - "Turing-complete"
- determinísticos
- criptomoeda: Ether (ETH)
    menor unidade: wei (1 ETH = 10^-18 wei)


### Transações
- para transferir Ethers (ETH)
- para publicar um smart contract (*deploy*)
- para executar alguma função de um smart contract já publicado


### Contratos Inteligentes e Fundamentos de Solidity
#### Contratos Inteligentes (*Smart Contracts*)
- programas computacionais
- publicados e executados no ambiente de uma blockchain
- imutáveis -> seguro
- autônomos (quando iniciado / chamado)
- sem intermediários

#### *Smart Contracts* no Ethereum
- compilados para a VM do Ethereum (EVM) e em seguida, gravados no blockchain
    - escrito em Solididy
    - compilado para *bytecode*

#### O que é imutável no *Smart Contract*?
- não pode corrigir o código!
- o smart contract pode ter funções para alterar dados
- não pode alterar o histórico: 
    - A informação pode ser registrada em um bloco
    - e pode ser apagada em outro
    - fica o histórico (auditoria)

## *Wallet* (Carteira)
- gerenciador de chaves usado para administrar criptomoedas ou tokens
- autorizar transações e interagir com páginas web ou aplicações descentralizadas (dApps)
- assinar mensagens demostrando que é o proprietário de um endereço da sua carteira

- Obs: Criptomoeda x Token
    - criptomoeda: token nativo da rede