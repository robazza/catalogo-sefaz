---
title: "Agrupamento 41"
descricao: |
 Verificar se a certidão emitida é oficial.
legislação:
  - Lei nº 7.186 de 2006
prazo: Pronto Atendimento
custo: Sem Custo
documentacao:
  - Código de Controle da Certidão

responsavel:
  coordenacao: CRC
  setor: SEATE
  nome: Carlos Augusto Silva Santos
  email: casantos@sefaz.salvador.ba.gov.br

canais:
  - 'Online/site'

hide:
  - toc
---


Validação da Certidão de Débito do Cadastro Imobiliário
Online	
Serviços Parcelamento	
Parcelamento de Débitos	
Consiste em efetuar o parcelamento de débito contido na Prefeitura	
Senha web e inscrição Municipal ou Imobiliária	



# {{ page.meta.title }}

## Descrição

{{ page.meta.descricao }}

## Canais de Atendimento


??? settings   "Online/site (clique para ver mais)"
    [Acesso ao Serviço Online](https://www.sefaz.salvador.ba.gov.br/IPTU/validaCertidaoDebito?Length=4){ .md-button }
	


## Documentação Exigida

{% for it in page.meta.documentacao %}
- [X] {{ it }}
{% endfor %}


## Custo

{{ page.meta.custo }}

## Prazo de Atendimento

{{ page.meta.prazo }}

## Coordenação Responsável

{{ page.meta.responsavel.coordenacao }}

## Setor Responsável

{{ page.meta.responsavel.setor }}

## Nome Responsável

{{ page.meta.responsavel.nome }}

## E-mail Responsável

{{ page.meta.responsavel.email }}

## Legislação Relacionada

{% for it in page.meta.legislação %}
- [X] {{ it }}
{% endfor %}
