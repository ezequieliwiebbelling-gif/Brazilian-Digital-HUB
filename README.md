# Brazilian Digital Hubs

Mapeando a convergência entre energia renovável e conectividade internacional no Brasil.

## Visão Geral

Brazilian Digital Hubs é uma plataforma interativa que cruza infraestrutura energética e conectividade digital para identificar regiões com potencial estratégico para implantação de data centers e infraestrutura digital.

O projeto nasceu a partir de uma pergunta simples:

"Se eu precisasse construir um data center no Brasil, onde energia e conectividade se encontram?"

Ao sobrepor mapas de geração eólica, armazenamento energético e cabos submarinos internacionais, surgiu um resultado inesperado:

Balneário Pinhal (RS).

---

## Principais Descobertas

Balneário Pinhal reúne simultaneamente:

- Cabo submarino internacional Malbec (Meta)
- 570,6 MW de geração eólica instalada
- 6.507 MW de potencial offshore
- Sistema BESS de 55 MW / 301 MWh

Essa combinação cria uma vantagem competitiva rara para infraestrutura digital.

---

## Funcionalidades

### Visualização Geoespacial

- Mapa interativo nacional
- Camadas de energia eólica
- Cabos submarinos internacionais
- Pontos de aterramento
- Centros de consumo

### Dashboard de Dados

- Consumo energético estimado
- Superávit energético
- Métricas por município
- Filtros dinâmicos

### Recursos Técnicos

- Choropleth por estado
- SVG customizados
- Ant Path Animation
- Busca em tempo real
- Responsividade
- Dark Mode

---

## Tecnologias Utilizadas

### Frontend

- HTML5
- CSS3
- JavaScript (Vanilla)
- Leaflet.js

### Data Science

- Python
- Pandas
- GeoPandas
- Folium
- Shapely

### Deploy

- Vercel

---

## Arquitetura

O projeto possui duas implementações.

### Python + Folium

Objetivo:
Demonstrar automação, análise de dados e geração programática de mapas.

Arquivo principal:

map_generator.py

---

### HTML + JavaScript

Objetivo:
Criar uma aplicação interativa com foco em experiência do usuário e produto final.

Arquivo principal:

index.html

---

## Aprendizados

Durante o desenvolvimento foram identificados e corrigidos diversos problemas relacionados a:

- Qualidade dos dados
- Georreferenciamento
- UX Mobile
- Performance
- Segurança Frontend
- Arquitetura de código

O projeto passou por múltiplas rodadas de auditoria técnica e revisão de código antes da publicação.

---

## Próximos Passos

- Integração com APIs em tempo real
- Dados energéticos atualizados automaticamente
- Banco de dados PostgreSQL/PostGIS
- Histórico temporal
- Comparação entre regiões
- Indicadores para data centers

---

## Acesso

Aplicação:

https://project-znlmm.vercel.app/

---

## Autor

Ezequiel Wiebbelling

Estudante de Ciências Econômicas

Interesses:

- Análise de Dados
- Economia
- Infraestrutura
- Energia
- Business Intelligence
- Tecnologia
