# Escrever Documentação

## 1. Introdução

 &nbsp;&nbsp;Escrever documentação se refere ao processo de escrever um conjunto de artigos técnicos que instruem o usuário ao utilizar o produto. Uma documentação bem-escrita deve guiar o usuário de novato a expert no uso da ferramenta.
 
 &nbsp;&nbsp;A documentação também será o primeiro lugar aonde seus usuários irão para qualquer dúvida ou problema que tiverem. Portanto, é importante garantir não só que seus usuários possam encontrar facilmente as respostas que procuram, mas também que estas sejam claras e completas. Idealmente, nenhum usuário irá visitar a mesma página duas vezes.

 &nbsp;&nbsp;A documentação pode ser dividida em dois tipos:
- Referencias técnicas: estas páginas tem o dever de introduzir uma funcionalidade do produto e detalhar todas as suas características, como parâmetros, formas de uso, resultados, e erros conhecidos.
- Tutorias e guias: o objetivo destas páginas é de treinar o usuário no uso do produto. Elas consistem de uma série de passos que irão guiar o usuário na resolução de um problema, de forma que ao final dele, o usuário estará mais capacitado para usar a ferramenta de forma independente.

 &nbsp;&nbsp;Documentação de sucesso irá utilizar ambos os tipos. 


## 2. Ator ferramentas e etc.
 
 &nbsp;&nbsp;Escrever documentação é responsabilidade do **produtor de conteúdo** devido a sua habilidade de escrever de forma que engaje seus devs, com auxílio opcional do  **advogado**, que irá fazer a comunicação com o time de desenvolvimento para compreensão da ferramenta.
 
 &nbsp;&nbsp;Sua documentação deve ser hospedada no mesmo local onde seu produto está disponibilizado. Se você tem uma webpage para seu produto, é lá que  seus usuários irão procurar a documentação. Se seu produto é acessado através de um repositório no GitHub, então é lá que ela deve ser encontrada.
 
 &nbsp;&nbsp;Ferramentas:
 
 &nbsp;&nbsp;O processo de escrever documentação se dará em três momentos:
- Na primeira release do produto, quando nenhuma documentação existe e deve ser criada do zero englobando todo o produto.
- A cada release subsequente do produto, de forma a adicionar referencias para as novas funcionalidades, e atualizar as páginas referentes a qualquer funcionalidade que foi modificada.
- Periodicamente, em resposta a feedback de usuários ou da análise de métricas, para melhorar a documentação existente.

## 3. Processos e diretrizes

<details>
<summary><strong>3.1. Fazer investigação técnica do produto</strong></summary>
 
 &nbsp;&nbsp;O primeiro passo no processo da escrita da documentação não se dá em uma página em branco, mas com o produto em si. Para poder escrever sobre ele, você deve conhecer intimamente cada pedaço, cada funcionalidade, cada botão e cada erro.
  <br>
  <br>
 &nbsp;&nbsp;Isso se dará em parte por comunicação com o time de desenvolvimento e em parte por experimentação direta com o produto.
  <br>
  <br>
 &nbsp;&nbsp;Para cumprir a parte mais técnica da atividade, deve-se compor uma lista completa e organizada de todas as partes do produto, de preferencia na mesma ordem que serão encontradas por um usuário ao abrir o produto. 
  <br>
  <br>
 &nbsp;&nbsp;Por exemplo, ao abrir o Microsoft Word, você encontra, no topo da tela, uma barra de ferramentas com algumas opções, “arquivo”, “página inicial”, “inserir”, etc. Ao listar as funcionalidades do Word, é útil anotar estas opções nesta ordem. Ao clicar em cada uma destas opções, novas ferramentas se mostram, como opções de fonte, parágrafo, etc. Na sua lista, cada uma dessas opções seriam sub-itens dos seus itens principais.
  <br>
  <br>
 &nbsp;&nbsp;Isso ajudará a organizar a sua documentação, de forma que o usuário consiga intuitivamente localizar a informação que procura da mesma forma que encontrou, no programa, a ferramenta em questão.
  <br>
  <br>
 &nbsp;&nbsp;Outro aspecto importante para se anotar nesta etapa são os erros conhecidos, inclusive seus códigos e mensagens.
  <br>
  <br>
 &nbsp;&nbsp;Para cada nova release do produto, é necessário repetir esse processo somente para as novas funcionalidades, ou aquelas que foram modificadas ou afetadas pelas mudanças.

</details>

<details>
<summary><strong>3.2. Fazer investigação empática do produto</strong></summary>
 
 &nbsp;&nbsp;Existe um outro aspecto da investigação do produto, menos técnico, que é o de experimentar o produto você mesmo. Sua função não é de ser um bug tester, clicando em cada botão trinta vezes para ver o que quebra, mas de ser o cliente zero, de utilizar o produto do mesmo jeito que um de seus usuários.
  
 &nbsp;&nbsp;Isso requer uma grande quantidade de empatia, pois seu objetivo é se colocar no lugar do usuário para poder antecipar tudo que sentirá, bem ou mal, ao usar o produto.
  
 &nbsp;&nbsp;Comece pensando em uma tarefa ou projeto que você imagina que seus usuários quererão fazer usando seu produto, e tente fazê-lo. Sua experiência será similar ao de seus clientes, então anote-a com cuidado, em particular as partes em que teve problemas ou dúvidas, pois estas possivelmente requerem uma explicação detalhada na documentação, enquanto que outras partes que conseguiu entender intuitivamente não precisam de tanto detalhe.
  
 &nbsp;&nbsp;Usando o Word novamente como exemplo, mudar o tamanho ou estilo da fonte é simples, e dificilmente requer explicação; ajustar as margens é um pouco mais complicado; e quantos de nós nunca tivemos uma dor de cabeça tremenda ao tentar formatar nossas imagens dentro de nosso texto? Dessa forma, mudar o tamanho da fonte não precisa de mais de uma frase na documentação, mas formatação de texto com imagens precisa de uma explicação detalhada.

</details>

<details>
<summary><strong>3.3. Organizar documentação</strong></summary>
 
 &nbsp;&nbsp;Tendo toda a experiência que você precisa para informar sua documentação, é hora de definir como ela será organizada na sua página. Esse passo é importante para garantir que tanto você quanto os seus clientes possam encontrar a página que precisam rapidamente. Quando seu cliente acessa sua documentação deve se deparar com uma lista de tópicos e categorias gerais, cada qual o leva para uma outra lista mais específica até que ele encontra aquilo que precisa.
  
 &nbsp;&nbsp;No seu computador, sem dúvida, existem pastas “Documentos” e “Imagens”. Ao navegar para a pasta de “Imagens”, você talvez encontre outras pastas “Fotos de viagem”, “Fotos de gatos”, “Memes”, etc. Dentro de “Fotos de viagem” você talvez tenha “Férias 2021”, “Férias 2020”, “Férias 2019” e assim por diante até que você encontre exatamente aquela foto que você tirou naquela viagem específica. É assim que seu cliente deve navegar até a página que procura.
  
 &nbsp;&nbsp;Comece organizando os tutoriais e guias, que são, relembrando, aquelas páginas que irão detalhar um passo-a-passo para resolver algum problema. Estes serão divididos em categorias baseadas nas possíveis atividades que o usuário fará no seu produto, se possíveis ordenadas baseado na ordem que o usuário as fará. Isso quer dizer que a primeira categoria na sua lista será sempre uma chamada “Começando” ou algo parecido, que irá conter os guias de como baixar e instalar o produto, assim como o Tutorial Inicial, que será discutido na próxima sessão.
  
 &nbsp;&nbsp;As categorias seguintes vão depender do seu produto. Por exemplo, se seu produto for um que permite que os usuários desenvolvam seus próprios aplicativos, cobrindo todo o ciclo de desenvolvimento, desde o primeiro código até o release, então provavelmente terá categorias como “Design de UI”, “Teste de bugs” e “Lançamento”, que podem ser organizados nesta ordem, pois é nesta ordem que o usuário passará por essas três etapas, entre outras.
  
 &nbsp;&nbsp;Você pode criar essa lista com apenas dois níveis, mas claro que você também pode dividir cada um desses tópicos em outros, seguindo os mesmos princípios. Por exemplo “Design de UI” pode ser dividido em “Design da tela inicial”, “Design da Tela de login”, etc.
  
 &nbsp;&nbsp;Ao fim da sua lista de categorias você pode adicionar uma única categoria para as referências técnicas, ou seja, para a explicação de cada funcionalidade. Esta categoria vai ser então subdividida de acordo com a lista que você fez na seção 4.3.1

</details>

<details>
<summary><strong>3.4. Escrever documentação</strong></summary>

 &nbsp;&nbsp;Existem algumas diferenças cruciais nas formas de se escrever tutoriais, guias e referências, mas a maior parte dos princípios se aplica em todos os três tipos.
  
 &nbsp;&nbsp;Para cada página que escrever você deve começar pensando sobre qual ponto exatamente será o seu texto. Então, dê um título à sua página que deixe perfeitamente claro qual será esse ponto. Em particular, se o texto em questão se referir a um daquelas partes do produto com que teve dificuldade, tente pensar em como o cliente que encontrasse essa dificuldade procuraria pela resposta. Que palavras ele usaria para formular esta pergunta? Use essa reflexão para criar o título, pois é dessa forma que o cliente irá procurar.
  
 &nbsp;&nbsp;Uma vez decidido o que irá ser escrito, procure dividir o texto em subseções, especialmente se a página for muito longa. Use cabeçalhos para dividir essa seção, que devem seguir os mesmos princípios do título de serem claros e instrutivos do que suas respectivas seções contêm.  Estes cabeçalhos ajudarão seus clientes a localizarem exatamente onde está sua necessidade. É possível que, em um processo de dez passos, ele teve dificuldade no passo nove, e, portanto, é muito melhor, para ele, ir diretamente para esse passo, do que ler o documento do início para poder encontra-lo.
  
 &nbsp;&nbsp;Agora que seu documento está organizado e esclarecido, você precisa escrevê-lo de fato. A forma de escrever vai depender muito do que exatamente se trata seu texto, e vamos cobrir algumas diretrizes importantes nas próximas seções, mas algo que se mantém para todo o texto é o cuidado com a linguagem. Como o público alvo da sua função são desenvolvedores você pode assumir um certo nível de conhecimento técnico da sua parte, mas mesmo assim, procure ser o mais didático possível em sua explicação. Lembre-se que mesmo desenvolvedores têm pontos cegos, assim como diferentes níveis de expertise. Um usuário pode ser um grande conhecedor de múltiplas linguagens de programação, mas ser novato justamente naquela que seu programa usa. E não se esqueça de que talvez sua documentação seja lida por pessoas que não são nativos da sua língua, e por isso terão um nível de compreensão mais baixo. Albert Einstein uma vez disse que você não entende uma tecnologia até que possa explica-la a sua avó, e essa é uma boa medida para ter em mente enquanto escreve.
  
 &nbsp;&nbsp;Princípios gerais de escrita também se aplicam. Obviamente, erros gramaticais e ortográficos são impensáveis. Procure usar palavras comuns e simples ao invés de um vocabulário muito rebuscado. Evite frases longas e complicadas, a repetição de palavras, gírias e regionalismos, e a voz passiva. A ferramenta grátis HemingwayApp pode ajudar você em todos esses pontos.
  
 &nbsp;&nbsp;Elimine a gordura do seu texto evitando se alongar sobre assuntos que não estão diretamente relacionados ao seu ponto. Foque no que precisa ser dito para que o leitor entenda o que você quer dizer. Ás vezes é possível delegar a informação que é importante, mas não imediatamente relevante. Se a funcionalidade em questão requer entendimento de cálculo numérico, você não precisa explicar cálculo numérico no seu texto, basta fazer um link para um recurso externo que explique por você.
  
 &nbsp;&nbsp;É importante evitar a duplicação de informação, pois esta pode aumentar e muito o custo da manutenção. Se certa funcionalidade é alterada em um release, você vai precisar atualizar cada página que trata dessa funcionalidade em sua documentação. Quanto mais dessas páginas existirem, mais difícil isso será. Por isso é bom ter em mente o mesmo princípio do parágrafo anterior e simplesmente apontar para outras páginas que contenham a informação, ao invés de repeti-la.
  
 &nbsp;&nbsp;Uma vez que esteja satisfeito com seu texto, é preciso ilustrá-lo com a ajuda de diagramas ou imagens. Uma destas vale mais do que mil palavras, então porque você deveria descrever em detalhes o layout de uma página para localizar um botão quando você pode simplesmente colocar uma captura de tela, e fazê-lo visualmente? Uma boa métrica é ter pelo menos uma imagem por cabeçalho, ou cada vez que, ao seguir seu guia ou tutorial, o usuário encontrar uma tela nova no programa. Uma imagem não precisa ser somente uma foto da tela, pode ser também um diagrama que ilustre um processo, por exemplo. Não se esqueça de escrever legendas acompanhando as imagens, isso é muito importante para pessoas com dificuldades visuais que usam leitores de tela.
  
 &nbsp;&nbsp;Feito isso, a sua página está pronta, mas faltam ainda alguns detalhes que ajudam e muito na organização e capacidade de pesquisa. O primeiro é o de relacionar páginas entre si. Crie no final da página uma seção de “veja também” com links para outras páginas de documentação que se relacionem de alguma forma com a atual. Por exemplo, se estiver escrevendo um tutorial para design de UI, você pode colocar um link para uma referência técnica da ferramenta técnica de design, e vice-versa. Isso ajuda não somente a evitar a duplicação de informação, quanto ajuda o usuário a encontrar mais recursos para ajuda-lo em seu trabalho. Lembre-se de fazer os links dos dois lados, se a página A aponta para a página B, é natural que B também aponte para A.
  
 &nbsp;&nbsp;Se sua ferramenta permitir, procure implementar um sistema de etiquetas, ou “tags”. Para cada página, pense em palavras-chaves que se relacionem ao texto e as adicione como rótulos, que permitam que a página seja buscada por esses termos. Da mesma forma que escreveu o texto, tente pensar nas palavras que o cliente usaria para encontrar a informação desta página.
  
 &nbsp;&nbsp;Garanta que a data em que escreveu cada página está visível, pois isso indicará aos seus leitores se ela está atual ou não.
Por fim, se o ambiente da sua documentação permitir, procure incorporar um sistema de curtidas e comentários. Isso o ajudará a medir o engajamento dos seus leitores e o sucesso da sua documentação.
  
  <details>
<summary><strong> &nbsp;&nbsp;3.4.1. Escrever tutoriais</strong></summary>

 &nbsp;&nbsp; &nbsp;&nbsp;Um tutorial é uma lista de instruções que guia o leitor na execução de uma atividade. O objetivo de um tutorial é familiarizar o leitor com diferentes aspectos da ferramenta de forma que, ao final dele, o leitor se sente empoderado para usá-la sozinho.
    
 &nbsp;&nbsp; &nbsp;&nbsp;Para escrever um tutorial, pense em um projeto que pode ser realizado pela sua ferramenta. Preferencialmente, tal projeto deve passar pelo maior número de funcionalidades possível. Usando novamente o exemplo de um programa para desenvolvimento de aplicativos, seu tutorial poderia ser um que ensina como criar um aplicativo simples, do início ao fim. Dessa forma, o usuário passará a conhecer todo o processo, assim como todas as funcionalidades que o possibilitam realiza-lo.
    
 &nbsp;&nbsp; &nbsp;&nbsp;Você não precisa explicar em detalhe cada botão que ele irá apertar (guarde isso para as referências técnicas), mas garanta que ele aperte o maior número de botões possível. Nem sempre será possível utilizar tudo, então priorize os que você acha mais importante.
    
 &nbsp;&nbsp; &nbsp;&nbsp;Tome muito cuidado para dar espaço para possíveis erros de interpretação. Ao seguir os seus passos, o leitor deve sempre chegar no mesmo resultado; se não conseguiu por erro de interpretação dele, a culpa é sua. O mesmo princípio vale para leitores usando ambientes diferentes. Um usuário no Windows deve obter o mesmo resultado de um no Linux. Se sua ferramenta possui alguma diferença com relação a sistema operacional, linguagem de programação ou outro fator, isso deve estar assinalado claramente no tutorial.
    
 &nbsp;&nbsp; &nbsp;&nbsp;A última diretriz para a criação de um bom tutorial, é a de que cada passo deve ter um resultado visível. Evite passos abstratos ou que lidem muito com o back-end, em partes que não estão acessíveis ao usuário. Se o usuário aperta um botão, deve perceber um resultado. Note que isso é algo que você pode recomendar ao time de desenvolvimento que incorpore esse princípio.
    
 &nbsp;&nbsp; &nbsp;&nbsp;O primeiro e mais importante tutorial que você precisa escrever é um chamado “Começando” ou algo parecido. Este tutorial deve levar o leitor dos primeiros passos ao usar a ferramenta até a realização de um projeto simples.
    
 &nbsp;&nbsp; &nbsp;&nbsp;Este é o único tutorial que você realmente precisa ter em sua documentação, mas você sempre pode escrever mais que cubram outros aspectos.

</details>
  
  <details>
 <summary><strong> &nbsp;&nbsp;3.4.2Escrever guias</strong></summary>

  &nbsp;&nbsp; &nbsp;&nbsp;Um guia é também um passo-a-passo para realização de uma tarefa, mas difere do tutorial em seu escopo.
    
  &nbsp;&nbsp; &nbsp;&nbsp;Ao contrário de um tutorial, que cobre um processo inteiro do início ao fim, um guia é focado em uma atividade específica. “Como salvar meu projeto”, “Como adicionar um gráfico”, etc, são exemplos de guias.
    
  &nbsp;&nbsp; &nbsp;&nbsp;Pense em atividade granulares que serão frequentemente realizadas pelos seus usuários independente do projeto. Escreva seus guias focados na atividade, com o mínimo de passos necessários.
    
  &nbsp;&nbsp; &nbsp;&nbsp;Fora isso, os mesmos princípios de escrita descritos anteriormente se aplicam.

 </details>

  <details>
<summary><strong> &nbsp;&nbsp;3.4.3 Escrever referências</strong></summary>

 &nbsp;&nbsp; &nbsp;&nbsp;Referências são explicações técnicas das diferentes funcionalidades do seu produto. É a parte mais simples porém mais tediosa de se escrever.
    
 &nbsp;&nbsp; &nbsp;&nbsp;Para escrever boas referências, basta certificar-se de que está cobrindo tudo que pode ser dito sobre cada aspecto, inclusive parâmetros, o que recebe, e o que faz, como usar e erros conhecidos.
    
 &nbsp;&nbsp; &nbsp;&nbsp;Lembre-se de incluir os códigos de erro, assim como o que fazer o encontra-los. Há duas formas de você incorporar os erros nas suas referências: você pode incluí-los na página relevante (por exemplo, erros que acontecem na seção de design de UI se encontram nas referências sobre design de UI), ou criar uma página específica para todos os erros e simplesmente apontar para esta página sempre que for relevante.
    
 &nbsp;&nbsp; &nbsp;&nbsp;Fora isso, os mesmos princípios de escrita descritos nas seções anteriores se aplicam.

</details>

  <details>
<summary><strong> &nbsp;&nbsp;3.4.4 Escrever exemplos de código</strong></summary>

 &nbsp;&nbsp; &nbsp;&nbsp;Um passo opcional que você pode querer dar na sua documentação é incluir exemplos de código. Estes chamam a atenção dos seus leitores e talvez possam ajuda-los muito mais que os textos mais bem escritos.
    
 &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp;Escrever estes exemplos vai depender muito do seu produto, mas alguns princípios são universais.
    
 &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp;Escreva exemplos que resolvam algum problema real, que você espera que os seus usuários encontrem. Não adianta o código ser bonito e impressionante se nunca será usado na prática.
    
 &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp;Espere que seu código seja copiado e colado com frequência. O que isso significa é que seu código deve funcionar independente de onde seja colocado. Por exemplo, não escreva código que referencie ou acesse uma pasta que só existe no seu computador, ou que só funciona em dados sistemas operacionais.
    
 &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp;Por fim, escreva um código limpo e de fácil compreensão. Deixe de lado as suas mal práticas de escrita de código e comente todas as linhas.
    
 &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp;Se a plataforma onde está disponibilizando sua documentação permitir, faça com que o código possa ser testado direto na página.

</details>


</details>

<details>
<summary><strong>3.5. Revisar documentação</strong></summary>

 &nbsp;&nbsp;Terminar a documentação inicial será uma grande vitória, mas não quer dizer que você nunca mais irá precisar tocar nela.
  
 &nbsp;&nbsp;Ao longo de seu trabalho como DevRel, você irá perceber que muitas vezes a sua documentação precisa de umas mudanças, seja porque está desatualizada, seja porque ela não estava muito boa para começar.
  
 &nbsp;&nbsp;Existem duas atividades de revisão de documentação: atualização, que deve ser feita a cada release significativo do seu produto; e correção, que deve ser feita a períodos regulares de sua preferência.

  
<details>
<summary><strong> &nbsp;&nbsp;3.5.1 Atualizar documentação</strong></summary>

 &nbsp;&nbsp; &nbsp;&nbsp;A cada nova release de seu produto, é de se esperar que ele passe por uma ou mais mudanças significativas, seja a adição de novas funcionalidades ou a melhoria das existentes. Sendo assim, sua documentação deve ser atualizada para não ficar para trás.
  
 &nbsp;&nbsp; &nbsp;&nbsp;Para cada nova funcionalidade, você deve criar novas referências técnicas e um ou dois guias que demonstrem seu uso. Para fazer isso, basta seguir as diretrizes das seções anteriores.
  
 &nbsp;&nbsp; &nbsp;&nbsp;Se alguma funcionalidade existente teve seu comportamento modificado de alguma forma, você deve encontrar as páginas que fazem referência a ela e editá-las para refletir o estado atual do produto. É nesta hora que a falta de duplicação de informação e os links para as páginas relacionadas serão de grande ajuda para você.
  
 &nbsp;&nbsp; &nbsp;&nbsp;Algo que você também pode incluir na sua documentação a partir da segunda revisão, em parceria com o time de suporte e o gerente da comunidade, é uma seção de Perguntas Frequentes. Idealmente, essas perguntas deveriam ser respondidas pela própria documentação, e ter uma seção dedicada para elas arrisca duplicar a informação, mas a realidade é que muitos usuários irão procurar por essa seção antes de qualquer outra, então pode ser útil tê-la.

</details>
  
  
<details>
<summary><strong> &nbsp;&nbsp;3.5.2 Corrigir documentação</strong></summary>

 &nbsp;&nbsp; &nbsp;&nbsp;Durante seu tempo no time de DevRel, você irá receber feedback da sua comunidade de diversas formas, algumas delas sobre documentação. Falaremos mais sobre essa coleta de feedback na próxima seção.
  
 &nbsp;&nbsp; &nbsp;&nbsp;A períodos semi-regulares, que podem variar de a cada semana até a cada ano, dependendo da quantidade de feedback que recebe, é importante revisar a documentação para entender o que pode ser melhorado.
  
 &nbsp;&nbsp; &nbsp;&nbsp;Ás vezes você irá perceber que certo guia ou tutorial não está muito claro, e muitos dos seus leitores não estão conseguindo cumpri-lo efetivamente. Nesse caso, talvez mais imagens, ou um passo a passo mais mastigado possa ajudar.
  
 &nbsp;&nbsp; &nbsp;&nbsp;Você pode perceber que alguns dos seus usuários estão procurando uma informação e não estão encontrando, o que pode significar que sua documentação precisa ser melhor organizada, ou que tal informação realmente não está em nenhum lugar e precisa ser adicionada.
  
 &nbsp;&nbsp; &nbsp;&nbsp;É importante analisar como seus usuários estão interagindo com sua documentação e com seu produto, qual a fonte de suas dificuldades, e tomar uma atitude de acordo.

</details>
  
  
<details>
<summary><strong> &nbsp;&nbsp;3.5.3 Criar listas de acesso rápido</strong></summary>

 &nbsp;&nbsp; &nbsp;&nbsp;Uma característica pequena mas de grande utilidade que você pode incorporar na sua documentação, mas só a partir da segunda revisão é uma lista de acesso rápido.
 
 &nbsp;&nbsp; &nbsp;&nbsp;Na página inicial, crie duas listas de links: uma para páginas atualizadas recentemente, outra para as páginas mais visitadas.
  
 &nbsp;&nbsp; &nbsp;&nbsp;A primeira lista permitirá que seus leitores acessem rapidamente a informação sobre como o seu produto mudou desde a última vez que usaram. A segunda lista facilitará que seus usuários encontrem respostas para dúvidas frequentes. Se muitas pessoas acessaram a página sobre design de UI, é natural assumir que, no futuro, muitas outras pessoas quererão o mesmo.
  
 &nbsp;&nbsp; &nbsp;&nbsp;Naturalmente, você só poderá criar essas listas a partir da segunda versão da sua documentação, e você deve mantê-la atualizada a cada revisão.

</details>
  
</details>

<details>
<summary><strong>3.6. Coletar métricas de sucesso</strong></summary>

 &nbsp;&nbsp;Como sempre, definir as métricas de sucesso dependem da definição de sucesso da atividade. Qual o propósito da documentação, e o faz com que ela tenha sucesso? Objetivo da documentação é instruir os leitores no uso da sua ferramenta, de forma a empoderá-los a se tornarem desenvolvedores melhores com ela.
  
 &nbsp;&nbsp;Então como você pode medir isso? Bom, se seu ambiente possui um sistema de curtidas e comentários, esse será o seu primeiro indicador de como seus leitores se sentem sobre sua documentação. Comentários em especial são os mais úteis, mas muitas poucas pessoas se dão o trabalho de escrevê-los, estando satisfeitas ou não. O número de curtidas também pode ser uma métrica esclarecedora sobre o quanto seus leitores estão felizes com cada página. Entretanto, lembre-se que números absolutos são enganadores, uma página pode ter menos curtidas simplesmente por ser menos visitada, mas possui uma razão de curtidas maior.
  
 &nbsp;&nbsp;Mas a informação mais interessante virá de uma análise das estatísticas de visitação da página. Algumas das ferramentas citadas na seção 4.2 já oferecem esse serviço, mas para a maior parte dos casos a ferramenta grátis Google Analytics irá cobrir suas necessidades. Dentre essas estatísticas você irá encontrar informação como quantas pessoas visitaram cada página, quanto tempo permaneceram nela, e quantos visitantes são repetidos.
  
 &nbsp;&nbsp;Note que esses dados brutos podem ser enganadores sem uma interpretação inteligente. Uma página recebendo muitos visitantes pode ser sinal de sucesso, mas depende da página e da sua interpretação. Se o seu guia para desinstalação do produto está recebendo muitos visitantes, isso pode ser um mal sinal. Ao mesmo tempo, um guia recebendo poucos visitantes pode ser um sinal de que os leitores não o estão encontrando, ou pode indicar que a funcionalidade explicada é tão intuitiva que ninguém sente a necessidade de lê-lo. Você precisaria fazer uma análise da sua comunidade para entender o que está acontecendo. Se uma página está recebendo poucos visitantes, mas você e seu time de suporte estão recebendo muitas perguntas que podem ser respondidas por aquela página, é um sinal de que ela não está sendo encontrada. Por outro lado, uma página recebendo muitos visitantes pode ser uma indicação de que certa área do produto pode ser redesenhada para ser mais intuitiva.
  
 &nbsp;&nbsp;Uma informação talvez mais útil é a de visitantes repetidos. Se uma página recebe muitos leitores que só a visualizam uma vez, isso indica que ela está esclarecendo suas dúvidas. Mas se os mesmos leitores ficam constantemente voltando a ela, isso quer dizer que a primeira visita não resolveu seu problema, o que indica que ela está confusa ou incorreta.
  
 &nbsp;&nbsp;Por fim, você pode estudar métricas provenientes de fora da documentação em si. Você pode buscar em áreas como tíquetes de suporte, ou na própria discussão acontecendo nos fóruns da sua comunidade. Se perceber muitas questões ou pedidos de ajuda do mesmo assunto, você pode tentar aprimorar a documentação que trata desse assunto, e depois medir se houve uma diminuição no número de questões relacionadas.
  
 &nbsp;&nbsp;Essas métricas de sucesso irão lhe dizer que correções você deve fazer na sua documentação (seção 4.3.5.2). Depois, ao fim de um novo período, você deve examinar as mesmas métricas e verificar se houve alguma diferença depois das suas correções ou não.

</details>

## 4. Diagramas

### 4.1. No primeiro release do produto
<br>

![Image](https://i.imgur.com/zIWrt86.png)
<br>
### 4.2. Depois de cada release subsequente
<br>

![Image](https://i.imgur.com/Bp2bucC.png)
<br>
### 4.3. Periodicamente
<br>

![Image](https://i.imgur.com/1sLi7Qf.png)
<br>

## 5. Checklist

### 5.1. Fazer investigação técnica do produto
  
- <input type="checkbox" name="uchk">  Você tem uma noção básica do produto, suas funcionalidades e seu propósito?

- <input type="checkbox" name="uchk"> Você possui uma lista indicando todas as funcionalidades do produto de forma completa?

- <input type="checkbox" name="uchk"> Essa lista está organizada de forma a refletir a estrutura do produto

- <input type="checkbox" name="uchk"> Você saberia explicar, um por um, o funcionamento de todos os elementos dessa lista?

- <input type="checkbox" name="uchk"> Você anotou todos os erros conhecidos, seus códigos, mensagens, efeitos e soluções?

- <input type="checkbox" name="uchk"> Você esteve em contato com o time de desenvolvimento para averiguar a completude de sua lista?

### 5.2. Fazer investigação empática do produto

- <input type="checkbox" name="uchk"> Você consegue identificar as razões pelas quais alguém usaria seu produto, e o que tentariam fazer com ele?

- <input type="checkbox" name="uchk"> Você tentou reproduzir esse processo hipotético?

- <input type="checkbox" name="uchk"> Você anotou suas experiências ao usar o produto? O que foi bom, o que foi ruim, o que foi prazeroso, o que foi difícil de entender?

- <input type="checkbox" name="uchk"> Você saberia, com assistência do time de desenvolvimento, guiar um novo usuário tentando fazer a mesma coisa de forma que ele não tivesse os mesmos problemas que você?

### 5.3. Organizar documentação

- <input type="checkbox" name="uchk"> Você possui uma lista de atividades que irá detalhar por meio de guias e tutoriais?

- <input type="checkbox" name="uchk"> Esta lista está separada por processo ou de outra forma intuitiva?

- <input type="checkbox" name="uchk"> Esta lista está ordenada de forma a refletir o uso natural do seu produto?

- <input type="checkbox" name="uchk"> O seu repositório de documentação está organizado da mesma forma?

- <input type="checkbox" name="uchk"> Você possui, no seu repositório, uma seção para armazenar as referências técnicas?

- <input type="checkbox" name="uchk"> Esta seção está subdividida e ordenada de forma a refletir a estrutura do seu produto?


### 5.4. Escrever documentação

- <input type="checkbox" name="uchk"> Você deu ao seu documento um título claro e instrutivo?

- <input type="checkbox" name="uchk"> No título, você usou uma ou mais palavras-chaves pelas quais o seu documento pode ser facilmente buscado e encontrado?

- <input type="checkbox" name="uchk"> Seu documento está subdividido por meio de cabeçalhos também claros e instrutivos?

- <input type="checkbox" name="uchk"> Seu texto pode ser compreendido por leitores de diferentes níveis de conhecimento técnico?

- <input type="checkbox" name="uchk"> Seu texto está livre de erros ortográficos e gramaticais?

- <input type="checkbox" name="uchk"> Seu texto está livre de gírias e regionalismo?

- <input type="checkbox" name="uchk"> Seu texto está livre de frases demasiado longas?

- <input type="checkbox" name="uchk"> Seu texto está livre da voz passiva?

- <input type="checkbox" name="uchk"> Seu texto está focado no objetivo, sem se alongar sobre assuntos tangenciais?

- <input type="checkbox" name="uchk"> Seu texto está livre de informação duplicada em alguma outra página?

- <input type="checkbox" name="uchk"> Seu texto possui imagens e diagramas ilustrativos?

- <input type="checkbox" name="uchk"> Estas imagens possuem legenda?

- <input type="checkbox" name="uchk"> Sua página possui links para outras páginas de conteúdo similar ou relacionado?

- <input type="checkbox" name="uchk"> Sua página possui etiquetas que facilitarão sua busca?

- <input type="checkbox" name="uchk"> Sua página mostra a data em que foi escrita ou atualizada?

- <input type="checkbox" name="uchk"> Sua página pode ser curtida ou comentada?

**Escrever tutoriais**

- <input type="checkbox" name="uchk"> Seu tutorial cobre o processo ao que se refere do início ao fim?

- <input type="checkbox" name="uchk"> Sue tutorial passa pelo maior número de funcionalidades possível, priorizando as mais importantes?

- <input type="checkbox" name="uchk"> Seu tutorial pode ser seguido da mesma forma por usuários em diferentes sistemas operacionais?

- <input type="checkbox" name="uchk"> Seu tutorial está detalhado de forma a impedir erros de interpretação?

- <input type="checkbox" name="uchk"> Cada passo do seu tutorial tem um resultado visível?

**Escrever guias**

- <input type="checkbox" name="uchk"> Seu guia está focado em uma atividade concreta?

- <input type="checkbox" name="uchk"> Seu guia pode ser seguido da mesma forma por usuários em diferentes sistemas operacionais?

- <input type="checkbox" name="uchk"> Seu guia está detalhado de forma a impedir erros de interpretação?


**Escrever referências**

- <input type="checkbox" name="uchk"> Sua referência detalha o funcionamento de dado aspecto do produto?

- <input type="checkbox" name="uchk"> Parâmetros de entrada?

- <input type="checkbox" name="uchk"> Possíveis configurações e opções?

- <input type="checkbox" name="uchk"> Forma correta de uso?

- <input type="checkbox" name="uchk"> Resultados?

- <input type="checkbox" name="uchk"> Erros conhecidos? (incluindo código, mensagem e solução recomendada)

**Escrever exemplos de código**

- <input type="checkbox" name="uchk"> Seu código está claro, e conciso, livre de mal práticas de código?

- <input type="checkbox" name="uchk"> Seu código pode ser copiado e colado sem afetar seu desempenho?

- <input type="checkbox" name="uchk"> Seu código está bem comentado?

- <input type="checkbox" name="uchk"> Seu código pode ser testado direto na página?


### 5.5. Revisar documentação

**Atualizar documentação**

- <input type="checkbox" name="uchk"> Existem funcionalidades completamente novas no novo release do produto?

- <input type="checkbox" name="uchk"> Estas novas funcionalidades foram documentadas seguindo os mesmos passos das primeiras?

- <input type="checkbox" name="uchk"> Alguma funcionalidade existente foi modificada?

- <input type="checkbox" name="uchk"> Todas as páginas que fazem referência a essa funcionalidade foram editadas para refletir seu estado atual?


**Corrigir documentação**

- <input type="checkbox" name="uchk"> Ao examinar as métricas de sucesso, ficou claro que alguma parte da documentação não está cumprindo seu papel?

- <input type="checkbox" name="uchk"> A documentação foi corrigida de forma a melhor alcançar seu objetivo?

**Criar lista de acesso rápido**

- <input type="checkbox" name="uchk"> Você criou e/ou atualizou uma lista de pelo menos cinco páginas que foram mais visitadas no último período, com links para as mesmas?

- <input type="checkbox" name="uchk"> Você criou uma lista similar para páginas recém-atualizadas?

### 5.6. Coletar métricas de sucesso

- <input type="checkbox" name="uchk"> Caso se aplique, você leu os comentários nas suas páginas?

- <input type="checkbox" name="uchk"> Caso se aplique, você verificou quantas curtidas relativas ao número de leitores recebeu cada página?

- <input type="checkbox" name="uchk"> Você verificou quantas pessoas visitaram cada página? Qual foi a mais vista e a menos vista?

- <input type="checkbox" name="uchk"> Você verificou quanto tempo, em média, os leitores se demoram em cada página?

- <input type="checkbox" name="uchk"> Você verificou quais páginas tendem a receber visitantes repetidos?

- <input type="checkbox" name="uchk"> Você verificou outros canais de feedback da comunidade (fóruns, tíquetes de suporte, etc.) para perceber se existem dúvidas frequentes que podem ser respondidas pela documentação?

- <input type="checkbox" name="uchk"> Você consegue extrair, de toda essa informação, alguma dica de como a sua documentação está falhando em atender as necessidades de seus usuários?


