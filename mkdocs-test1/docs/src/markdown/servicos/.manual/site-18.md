---
title: "Emissão de Certidão Positiva com efeitos de Negativa"
descricao: |
 Emissão de documento certificando que existe débitos do contribuinte, contudo o contribuinte entrou em acordo com a SEFAZ.
legislação:
  - Lei nº 7.186 de 2006
prazo: Pronto Atendimento
custo: Sem Custo
documentacao:
  - Inscrição Imobiliária ou Municipal (CGA)
  - CPF 
  - CNPJ

responsavel:
  coordenacao: CRC
  setor: SEATE
  nome: Carlos Augusto Silva Santos
  email: casantos@sefaz.salvador.ba.gov.br

canais:
  - 'Online/site'
  - 'e-mail'

hide:
  - toc
---

# {{ page.meta.title }}

## Descrição

{{ page.meta.descricao }}

## Canais de Atendimento

??? settings   "Presencial (clique para ver mais)" 

	Unidades que oferecem o serviço:
	
	- [X] Posto Central - SEDE
	- [X] Postos SAC's
	- [X] Postos Prefeitura Bairro

??? settings   "Online/site (clique para ver mais)"
    [Acesso ao Serviço Online](https://www.sefaz.salvador.ba.gov.br/imobiliario/Certidao/Pesquisar?funcao=UC00100){ .md-button }
	
	O acesso a esse serviço é feito após login no portal E-SEFAZ.
	
??? settings   "E-mail (clique para ver mais)"
    Envie e-mail para xxxx@sefaz.salvador.ba.gov.br com o título "{{ page.meta.title }}" e anexe foto legível dos documentos listados em Documentação Exigida.
	O atendente manterá o contato via e-mail para atendimento a solicitação.




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
