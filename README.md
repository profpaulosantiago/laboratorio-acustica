# Laboratório de Acústica

Ferramenta didática de Acústica para o Ensino Médio (Física IV, IFCE). Monte timbres somando senos, toque notas, equalize sons e acompanhe, em tempo real, o espectro e a forma de onda.

**Acesse:** https://profpaulosantiago.github.io/laboratorio-acustica/

## Abas

- **Timbres**: compositor de timbres. Cada componente é um termo A·sen(2π·f·t + φ), com controles de frequência, amplitude (linear ou em dB) e fase, e um gráfico próprio. No topo, a forma de onda resultante e o espectro. Inclui mais de 30 timbres prontos (formas de onda clássicas, sopros, cordas, vozes, percussão afinada e fenômenos como batimento e fundamental ausente), colagem de picos medidos no Friture e opção de salvar e abrir timbres.
- **Teclado**: 12 teclas com seletor de oitava, sustentação e instrumento, inclusive o timbre montado na aba Timbres.
- **Equalizador**: 12 amostras sintetizadas, equalizador de 10 bandas, filtros passa-altas e passa-baixas, presets comerciais e didáticos, espectro e forma de onda em tempo real.
- **SpectroGame**: jogo de ouvido para 1 a 4 jogadores.
- **Conceitos**: documentação com os fundamentos e o funcionamento de cada recurso.

## Publicação

Basta o arquivo `index.html` na raiz do repositório e o GitHub Pages ativado em **Settings → Pages → Deploy from a branch → main / (root)**.

Feito com a Web Audio API, sem bibliotecas externas e sem gravações: todos os sons são gerados por síntese.
