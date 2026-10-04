# Treino de cirílico

App para aprender a **ler** o alfabeto cirílico russo, feito para jogar GeoGuessr. O objetivo é
decodificar placas de rua, fachadas e sinalização no Street View, não falar russo.

**Treino:** https://fabrizioloes.github.io/cirilico/
**Tutorial para quem nunca viu cirílico:** https://fabrizioloes.github.io/cirilico/tutorial.html

Abre no navegador do computador ou do celular, sem conta e sem instalar nada. O progresso fica
guardado no próprio aparelho.

## Como funciona

Aparece uma palavra ou frase em cirílico e você digita a transliteração, ou só diz se reconheceu.
Ao revelar, o app mostra a pronúncia, a tradução e, se você errou, a primeira letra onde a leitura
divergiu.

- **Mais de 3.300 cartas.** Palavras de placa, endereço, trânsito, cidades, regiões, marcas e
  vocabulário geral, mais frases do dia a dia, em 76 categorias.
- **Repetição espaçada.** Cada carta sobe uma caixa quando você acerta e volta ao início quando erra.
  As que você já domina aparecem bem menos.
- **Correção tolerante.** `ulica`, `ulitsa` e `ulitsa'` são aceitas para `улица`. O que importa é ter
  lido certo, não a convenção de transliteração.
- **Quatro níveis de dificuldade**, calculados pelo tamanho da palavra e pelas letras que mais
  atrapalham a leitura.
- **Partidas** por número de cartas, por tempo ou por tema, com placar e histórico.
- **Modo vizinhos.** Uma palavra de outra língua cirílica e você diz de que país ela é (Ucrânia,
  Belarus, Sérvia, Macedônia do Norte, Cazaquistão ou Bulgária), pela letra que só aquele país usa.
- **Tabela do alfabeto** com o som de cada letra, exemplo em português e as letras que enganam
  (В, Н, Р, С, У, Х).

## O que tem neste repositório

| Arquivo | O que é |
|---|---|
| `index.html` | O app inteiro num arquivo só, que funciona offline |
| `tutorial.html` | O tutorial, em sete blocos, das letras que já parecem latinas às palavras de placa |

O `index.html` é gerado por um script em Python a partir das listas de palavras, que ficam fora
daqui. Por isso não se edita à mão.
