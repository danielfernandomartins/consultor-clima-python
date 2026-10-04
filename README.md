# 🌦️ Consultor de Clima via API em Python

Aplicação que consulta uma cidade, obtém sua localização e busca condições climáticas atuais por meio de API externa.

## Problema

Combinar dados de localização com dados climáticos em um único fluxo de consulta.

## Funcionalidades

- Busca de cidade
- Latitude e longitude
- Estado e país
- Temperatura
- Sensação térmica
- Umidade
- Velocidade do vento
- Tratamento de cidade não encontrada

## Tecnologia

**Python • requests • Open-Meteo • JSON**

## O que demonstra

- Consumo de API
- Requisições HTTP
- Encadeamento de chamadas externas
- Manipulação de JSON
- Tratamento de erro

## Visão para Operações de TI

O fluxo depende de mais de uma chamada externa, o que ajuda a praticar análise de dependências. Uma falha pode ocorrer na busca da cidade, na obtenção das coordenadas ou na consulta climática.

### Como eu investigaria uma falha

- Confirmaria em qual etapa o erro ocorreu
- Verificaria status HTTP
- Validaria parâmetros enviados
- Conferiria dados retornados pela primeira API
- Testaria a segunda chamada isoladamente
- Diferenciaria falha local de indisponibilidade externa

## Como explicar em entrevista

> "Esse projeto me ajudou a pensar em troubleshooting por etapas. Como uma chamada depende da anterior, eu preciso identificar exatamente onde o fluxo parou. Isso é muito parecido com suporte a integrações: isolar componente, validar entrada, checar resposta e localizar a origem da falha."

## Autor

**Daniel Fernando Martins**
