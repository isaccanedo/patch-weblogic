# Atualização de Patch - Oracle WebLogic 12.2.1.4.0

Este documento descreve o processo de aplicação de um patch para o Oracle WebLogic Server 12.2.1.4.0.

## Pré-requisitos

- Oracle WebLogic Server 12.2.1.4.0 instalado
- Acesso à conta My Oracle Support
- OPatch utilitário atualizado (versão mínima requerida: 13.9.4.2.5)

## Passo 1: Download do Patch

1. Acesse [My Oracle Support](https://support.oracle.com/)
2. Navegue até a seção "Patches & Updates"
3. Busque pelo patch específico para WebLogic 12.2.1.4.0
4. Faça o download do arquivo zip do patch

Nota: O link exato e o número do patch variam dependendo do patch específico que você está aplicando. Verifique sempre a documentação mais recente no My Oracle Support.

## Passo 2: Preparação

1. Pare todos os serviços WebLogic e processos relacionados
2. Faça backup do seu domínio WebLogic e da instalação

## Passo 3: Extração do Patch

1. Copie o arquivo zip do patch para o servidor onde o WebLogic está instalado
2. Extraia o conteúdo do zip:
