# Laboratório de Acústica

Ferramenta didática de Acústica para o Ensino Médio (Física IV, IFCE). Monte timbres somando senoides, toque notas, equalize sons e acompanhe, em tempo real, o espectro e a forma de onda.

**Acesse:** https://profpaulosantiago.github.io/laboratorio-acustica/

## Seções

As seções ficam num menu lateral, aberto pelo ícone da mesa de som no canto superior esquerdo. No celular e no tablet, o botão **Compacto** mostra só o essencial de cada seção.

- **Timbres**: compositor de timbres. Cada senoide é um termo A·sen(2π·f·t + φ), com controles de frequência, amplitude (linear ou em dB) e fase, e um gráfico próprio; as múltiplas inteiras da mais grave recebem a etiqueta de fundamental ou harmônico. No topo, a forma de onda resultante e o espectro. Cada gráfico tem zoom independente no tempo e na amplitude, e o botão *Igualar escalas* põe todos na mesma escala. Inclui mais de 30 timbres prontos (formas de onda clássicas, sopros, cordas, vozes, percussão afinada e fenômenos como batimento e fundamental ausente), colagem de picos medidos no Friture e opção de salvar e abrir timbres.
- **Teclado**: 12 teclas com seletor de instrumento, oitava e sustentação.
- **Equalizador**: 12 amostras sintetizadas, equalizador de 10 bandas, filtros passa-altas e passa-baixas, presets comerciais e didáticos, espectro e forma de onda em tempo real.
- **SpectroGame**: jogo de ouvido para 1 a 4 jogadores.
- **Conceitos**: documentação com os fundamentos e o funcionamento de cada recurso.

## Publicação

Basta o arquivo `index.html` na raiz do repositório e o GitHub Pages ativado em **Settings → Pages → Deploy from a branch → main / (root)**.

Feito com a Web Audio API, sem bibliotecas externas e sem gravações: todos os sons são gerados por síntese.
