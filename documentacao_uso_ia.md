# Documentacao de uso de IA na atividade de portfolio

## Contexto da atividade

Esta atividade teve como objetivo construir o front-end de uma pagina pessoal de curriculo/portfolio, acompanhado de um guia de estilos e de interacoes na interface. O portfolio foi desenvolvido com HTML, CSS e JavaScript, mantendo os textos e imagens pessoais ja existentes no projeto.

A IA foi utilizada como apoio para transformar a interface em um portfolio visualmente mais consistente, organizar a estrutura, adaptar o estilo com base em uma referencia visual e verificar se a entrega atendia ao barema da atividade.

## Ferramentas e recursos utilizados

- HTML para a estrutura da pagina.
- CSS para identidade visual, layout, responsividade, cards, barras de habilidade e efeitos de hover.
- JavaScript para interacoes como modal de projetos, navegacao com destaque ativo, menu mobile, botao de voltar ao topo e animacao das barras.
- Imagens na pasta `assets`, incluindo foto de perfil e imagens dos projetos.
- IA generativa, por meio do Codex, para apoiar edicoes, revisoes, organizacao visual e documentacao.

## Prompts utilizados durante o processo

### Prompt 1: adaptacao visual com base em referencia

> com base nessa imagem de portifolio, entre pelo seguinte caminho de pastas /Documents/ponderada_portifolio/ponderada e modifique o todo html e css para ficar nesse estilo, mantendo os textos e as imagens que tem

Com esse prompt, a IA foi orientada a analisar uma imagem de referencia de portfolio em estilo escuro, com linhas brancas, blocos graficos, foto circular e composicao visual parecida com um poster. A partir disso, foram modificados o `index.html` e o `guiadeestilos.html`, mantendo o conteudo textual e as imagens existentes.

Principais alteracoes feitas:

- Fundo escuro com textura e linhas diagonais.
- Tipografia mais forte e visual de poster.
- Foto de perfil circular com borda branca.
- Cards e secoes com bordas brancas.
- Reorganizacao visual das secoes de contato, habilidades, projetos e footer.
- Ajuste do guia de estilos para acompanhar a nova identidade visual.

### Prompt 2: troca das imagens dos projetos e softwares

> modifuqe as imagens do projetos que sao clicaveis, para as imagens que adicionei na pasta de assets e na parte de software skills, adcione software skills que sejam coerentes com os projetos que realizei e altere os icones para ficarem condizentes

Neste momento, a IA verificou as imagens adicionadas na pasta `assets` e conectou cada uma aos cards clicaveis de projeto.

Imagens utilizadas:

- `assets/cieloVerso.png`
- `assets/publicaChain.png`
- `assets/coletivoTuring.png`

Tambem foram alteradas as habilidades de software para ficarem mais coerentes com os projetos realizados e com a area de interesse apresentada no portfolio.

Softwares e tecnologias destacados:

- JavaScript
- Python
- Solidity / Blockchain
- Node.js
- GitHub
- VS Code

Essa alteracao tornou a secao de software skills mais alinhada com projetos de backend, blockchain, programacao e ciberseguranca, em vez de manter uma lista voltada apenas a design visual.

### Prompt 3: ajuste das barras de habilidades

> na parte de habilidades tecnicas, coloque o mesmo efeito visual das barras que aparecem na parte de solidty, python e ciberseguranca

Com esse prompt, a IA ajustou as barras de habilidades tecnicas para que todas tivessem o mesmo efeito visual. A primeira tentativa utilizou variaveis CSS, mas o resultado nao apareceu corretamente na interface.

### Prompt 4: correcao do efeito das barras

> nao funcionou

A partir desse retorno, a IA corrigiu a implementacao de forma mais direta. As barras passaram a ter a largura definida diretamente no HTML, com `style="width:..."`, e o CSS recebeu um efeito visual unico aplicado a todas as barras.

O efeito final inclui:

- Preenchimento branco.
- Brilho.
- Textura diagonal.
- Animacao de varredura visual.
- Mesma aparencia para todas as habilidades tecnicas.

### Prompt 5: verificacao do barema

> verifique se meu portifolio e o guia de estilos atendem ao seguinte barema: [...]

Neste prompt, a IA analisou o portfolio e o guia de estilos com base nos criterios da atividade.

Foram verificados:

- Existencia do guia de estilos.
- Existencia do front-end do portfolio.
- Presenca de pelo menos tres interacoes diferentes.
- Coerencia entre guia visual e interface implementada.
- Legibilidade e navegabilidade.
- Pendencia do video obrigatorio.

Conclusao da verificacao:

- O portfolio atende ao requisito de front-end com mais de tres interacoes.
- O guia de estilos existe e cobre cores, tipografia, icones, componentes e interacoes.
- O video ainda precisa ser gravado para completar a entrega.
- Algumas descricoes do guia podem ser atualizadas para refletir exatamente a versao final da interface.

## Interacoes implementadas

O portfolio possui mais de tres interacoes, atendendo ao requisito minimo da atividade.

### 1. Navegacao com destaque ativo

A barra de navegacao permite acessar as secoes principais da pagina. Com JavaScript e `IntersectionObserver`, o item da navbar e destacado conforme a secao visivel na tela.

### 2. Menu mobile/dropdown

Em telas menores, a navegacao se adapta para um menu acionado por botao hamburguer, melhorando a responsividade e a navegabilidade.

### 3. Tooltips nos icones de software

Ao passar o mouse sobre os icones de software, aparece uma tooltip com o nome completo da tecnologia correspondente.

### 4. Barras de habilidades com efeito visual

As barras de habilidades tecnicas mostram o nivel de conhecimento em cada area, com preenchimento proporcional, brilho e efeito visual animado.

### 5. Modal nos projetos

Ao clicar em um card de projeto, abre-se um modal com nome, categoria, imagem e descricao do projeto.

### 6. Botao de voltar ao topo

Ao rolar a pagina, aparece um botao que permite retornar ao topo com rolagem suave.

## Como a IA ajudou no desenvolvimento

A IA foi utilizada como parceira de implementacao e revisao. O processo envolveu:

- Leitura da estrutura existente do projeto.
- Identificacao dos arquivos principais (`index.html` e `guiadeestilos.html`).
- Analise da imagem de referencia enviada.
- Adaptacao do HTML e CSS para um novo estilo visual.
- Preservacao dos textos e imagens pessoais ja existentes.
- Inclusao das novas imagens de projetos.
- Ajuste da secao de software skills para refletir melhor os projetos realizados.
- Correcao de problemas visuais apos feedback.
- Revisao da entrega com base no barema.
- Criacao desta documentacao.

## Relacao com o guia de estilos

O guia de estilos funciona como a referencia visual do portfolio. Ele apresenta os principais elementos usados na interface:

- Paleta de cores em preto, branco e tons de cinza.
- Tipografia usada em titulos, labels e textos.
- Icones de software e contato.
- Componentes como navbar, cards, tags e barras de habilidade.
- Exemplos de animacoes e interacoes.

Durante a implementacao, o portfolio foi ajustado para seguir essa linguagem visual: fundo escuro, bordas brancas, composicao em blocos e tipografia forte.

## Criterios de qualidade considerados

Durante o desenvolvimento, foram considerados os seguintes criterios:

- Legibilidade dos textos.
- Contraste entre texto e fundo.
- Navegabilidade entre secoes.
- Coerencia entre habilidades, projetos e softwares apresentados.
- Responsividade para diferentes tamanhos de tela.
- Uso de imagens reais dos projetos.
- Existencia de interacoes claras e demonstraveis.
- Organizacao visual consistente com a referencia.
- Preservacao do conteudo pessoal original.

## Pontos importantes para a apresentacao em video

No video de ate dois minutos, e recomendado explicar:

1. Que o portfolio foi construido com HTML, CSS e JavaScript.
2. Que o estilo visual foi baseado em uma referencia de portfolio em formato de poster escuro.
3. Que a IA foi usada para apoiar a transformacao visual, revisar o barema, ajustar interacoes e documentar o processo.
4. Que as principais interacoes sao: tooltips, modal dos projetos, navbar/menu, barras animadas e botao de voltar ao topo.
5. Que os projetos apresentados usam imagens reais da pasta `assets`.
6. Que os criterios de qualidade foram contraste, legibilidade, responsividade, navegabilidade e coerencia visual.

## Resumo final

A IA auxiliou principalmente na evolucao visual e funcional do portfolio. O projeto passou de uma estrutura inicial para uma interface mais autoral, com estilo grafico escuro, secoes bem definidas, projetos clicaveis, habilidades tecnicas coerentes e interacoes suficientes para atender ao barema.

Para finalizar a entrega, ainda e necessario gravar o video solicitado pela atividade, mostrando o rosto e explicando a interface, as interacoes, as ferramentas utilizadas e o processo de construcao.
