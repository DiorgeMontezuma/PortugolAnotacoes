<div align="center">
  
# ----------- OQUE SÃO ALGORITMOS? -----------
<div align="center">

  
> - ***Algoritmos são conjuntos de passos finitos e organizados que, quando executados, resolvem um determinado problema.***
> - ***Toda reprodução de padrão é conhecida como rotina, esse tema também é usado em algoritmos.***

<p align="center">
  <img width="450" src="https://guiatech.net/wp-content/uploads/2018/01/algoritmos-1.jpg">
</p>

<div align="center"> 

--- 
# ----------- ALGORITMOS SERVEM PARA O QUÊ? -----------
<div align="left">
  
> - Algoritmos servem para resolver problemas e executar tarefas de forma organizada e estruturada. 
> - Eles são conjuntos de passos finitos e bem definidos que, quando seguidos corretamente, permitem alcançar um objetivo específico

<details open>
  <summary>Veja Alguns exemplos de aplicativos e tecnologias que fazem parte do nosso dia a dia atualmente e usam algoritmos ↷</summary>

  |  | |
  | --- | --- |
  | **Redes Sociais** | _Os algoritmos são utilizados pelas redes sociais para decidir quais postagens, anúncios e recomendações de amigos ou páginas são mostrados no feed de notícias de cada usuário._ |
  | **Assistentes Virtuais** | _Algoritmos de processamento de linguagem natural são usados em assistentes virtuais como Siri, Google Assistant e Alexa para entender e responder às nossas perguntas e comandos._ |
  | **GPS e Navegação** | _Os aplicativos de navegação utilizam algoritmos para calcular a rota mais rápida e eficiente para chegar ao nosso destino, levando em consideração o tráfego e outras condições._ |
  | **Filtros de E-mails** | _Os algoritmos são empregados para identificar e filtrar e-mails indesejados (spam) em nossa caixa de entrada._ |
  | **Recomendações em Compras Online** | _Plataformas de comércio eletrônico utilizam algoritmos para sugerir produtos com base em nossas compras anteriores e interesses._ |

</details>

 ↻ Clique em "▶" Para abrir os exemplos ou fechar
<div>
<div align="center">
  
# ----------- EXEMPLOS -----------
Rotida do nosso cotidiano, Algoritmo hipotetico:

```mermaid
graph TD;
    
    X(Algoritmo para atravessar a rua)
    X-.->A(Olhar para direita)
    X-.->B(olhar para esquerda)
    A-->D
    B-->D{Se estiver vindo carro}
    D -->|Não| f[Atravesse] 
    D -->|Sim| g[Não atravesse]
```

```mermaid
graph TD;
    A(A lâmpada não funciona)
    A --> B{A lâmpada estava plugada?} 
    B -->|Não| C(Plugar a lâmpada)
    B -->|Sim| D{O bulbo queimou?} -->|Sim| E(Trocar o bulbo)
    D -->|Não| F(Comprar uma lãmpada nova)     
```

```mermaid
   graph TD;
   A(luminária não acende) -->B{Lâmpada está enroscada?}
   B -->|Nâo| C(Enroscar lâmpada)
   B -->|Sim| E{Lâmpada fundida?}
   E -->|Sim| F(Trocar lâmpada)
   E -->|Não| G(Comprar nova luminária)
     
     
```

```mermaid
graph TD;
   A([início]) --> B(Abrir forno)
   B --> C{forno aceso?}
   C -->|Não| D(Acender fogo)
   C -->|Sim| E(Botar lenha)
   D --> F
   E --> F
   F(assar o pão) --> G([Fim])
```

---

<div align="center">
