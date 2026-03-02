# PROJETO FINAL: MEU PRIMEIRO AMBIENTE VR
---

## Descrição Geral
Este projeto consiste em uma experiência de Realidade Virtual (VR) desenvolvida na Unity utilizando o Meta XR SDK. O ambiente simula um espaço interativo de lazer focado em esportes, permitindo ao usuário interagir com objetos físicos em uma cena otimizada para o Meta Quest.

## Como Executar o Projeto
1. **Requisitos:** Unity (versão compatível com Android Build Support) e Meta XR SDK.
2. **Clonar:** Baixe este repositório.
3. **Cena:** Abra a pasta `Assets/Scenes` e execute o arquivo `CenaPrincipal`.
4. **Build:** O projeto está configurado para plataforma Android. Para testar em VR, utilize o *Build and Run* com o dispositivo conectado.

## Considerações

### Conceito e Motivação
A ideia central do ambiente foi democratizar o acesso a desportos que, na realidade física, possuem barreiras de custo ou localização, como o boliche ou o ténis. O objetivo foi criar um espaço simples, mas funcional, onde a física fosse o elemento central da diversão.

### Decisões de Design e Assets
* **Ambiente:** Optou-se pelo modelo *LargeRoom* do próprio Meta SDK. A escolha visou manter o *poly count* baixo e garantir compatibilidade visual com o Skybox nativo da Meta, evitando problemas de performance com modelos externos pesados.
* **Metodologia Low Code:** O desenvolvimento priorizou o uso dos componentes nativos do Unity (Inspectors, Rigidbodies, Materials) em vez de scripts complexos em C#. Isso permitiu focar no entendimento profundo da *engine* e das propriedades físicas.

### Desafios e Soluções com Auxílio de IA
Utilizei ferramentas de IA como tutoras para superar obstáculos técnicos específicos, o que acelerou o aprendizado:
* **Física da Bola:** Inicialmente, as bolas deslizavam infinitamente. Aprendi a configurar o *Angular Drag* e criar *Physics Materials* para controlar o atrito e o quique.
* **Simulador:** Notei instabilidades visuais no simulador do Unity Editor, mas confirmei que as configurações de Build para Android garantem a estabilidade no dispositivo final.


## Créditos
- [Bola de basquete](https://sketchfab.com/3d-models/basketball-b7357866e35e4e1181e7488ae0577bdb);
- [Bola de boliche](https://sketchfab.com/3d-models/bowling-ball-fc8f1162901a4e38b506fe1ab229f296);
- [Pino de boliche](https://sketchfab.com/3d-models/bowling-pin-784499acc8a646318e11543a46132127);
- Raquete e bola de tênis : Meta Asset Store;
