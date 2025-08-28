# 🚆 Mapa Interativo de Estações e Apeadeiros

Este projeto apresenta um mapa interativo com todas as estações e apeadeiros de Portugal, usando [Leaflet](https://leafletjs.com/) e dados geográficos obtidos via [OpenStreetMap](https://www.openstreetmap.org/).

---

## 🗺️ Funcionalidades

- Visualização de estações e apeadeiros com ícones distintos
- Popups com informações detalhadas (nome, tipo, linha, município, distrito)
- Filtro interativo para mostrar/ocultar estações ou apeadeiros
- Legenda visual para facilitar a leitura do mapa

---

## 📂 Estrutura do projeto

---

## 🚀 Como usar

1. Abre o ficheiro `index.html` num navegador moderno.
2. O mapa será carregado com os dados de `estacoes_com_coords.json`.
3. Usa os filtros no canto superior esquerdo para mostrar apenas estações ou apeadeiros.
4. Clica nos marcadores para ver detalhes de cada ponto.

---

## 🧠 Como foram geradas as coordenadas

As coordenadas foram obtidas automaticamente usando a API [Nominatim](https://nominatim.openstreetmap.org/) com base nos campos:

- `Designação`
- `Freguesia`
- `Município`
- `Distrito`

Cada entrada foi convertida num endereço como:  
`"Maceda, Ovar, Aveiro, Portugal"` → latitude e longitude

---

## 🤝 Contribuir

Queres ajudar a melhorar o projeto?

- Corrigir ou adicionar estações
- Melhorar o visual do mapa
- Adicionar novas funcionalidades (ex: pesquisa por nome, agrupamento por linha)

Faz um fork, cria uma branch e envia um pull request!

---

## 📄 Licença

Este projeto é livre para uso e modificação. Os dados são públicos e baseados em fontes abertas.
