# Azure AI
## Análise de sentimentos com Language Studio no Azure AI
### Análise de texto 
- Fase 1 (Analisar o texto)
  A inteligência vai retirar do seu texto algumas informações como :
  - Idioma predominante
  - Sentimento
  - Frases-chave
  - Entidades<br>
  Exemplo prático:<br>
  ```Passei férias maravilhosas na França```<br>
  
| Info | Exemplo |
| -------- | ---------- |
| Idioma predominante | Português |
| Sentimentos | 0,88 (positivo) |
| Frases-chave | "férias maravilhosas" |
| Entidades | França |

A partir dessas informações é possivel entender, por exemplo:
- Que idioma está sendo falado
- A mensagem que está sendo transmitida é boa ou não
- Onde estavam
- O que estavam fazendo

## Respostas a perguntas
Para que sua inteligência consiga gerar respostas é importante que ela tenha uma **base de conhecimento**, podemos fazer isso das seguintes maneiras:
- Inserir informações de perguntas e respostas
- Documentação de perguntas frequentes
- Uso de bate-papo integrado

## Serviço de bot do Azure 
Permite criar, hospedar, gerenciar e conectar bots inteligentes na **nuvem**. Ele facilita o desenvolvimento de bots conversacionais que podem interagir com usuários por meio de diversos canais.
### Quando podemos usar ?
- Atendimento automatizado ao cliente
- Assistentes virtuais internos para empresas
- Bots para FAQs e suporte técnico
- Integração com sistemas corporativos
O Bot também usa o sistema de palavras/frases-chave e aproveita de diversas bases de conhecimento para seu bom funcionamento!

## Compreensão da linguagem coloquial
É a capacidade de um modelo de IA entender:

- Frases informais ou incompletas
- Gírias ou expressões regionais
- Ortografia errada ou abreviações comuns
### Base para a compreensão
- Entidade: <br>
É uma informação específica dentro do enunciado que você quer extrair — como nomes, valores, datas, números de conta, etc.
- Enunciado:<br>
É uma frase de exemplo que um usuário poderia dizer para expressar uma intenção.
- Intenção:<br>
É o objetivo do usuário ao dizer algo. Representa o que ele quer fazer.<br>
Exemplo prático:<br>
 ```Acenda a luz```<br>
  
| Base | Exemplo |
| -------- | ---------- |
| Enunciado | "Acenda a luz" |
| Entidade | Luz |
| Intenção | Acender a luz |

## Reconhecimento e síntese de fala
Esse recurso gera uma fala audível a partir de um texto. Usado em situações como:
- Auxílio para deficientes visuais
- Assistentes virtuais de carro

