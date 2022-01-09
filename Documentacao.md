# Escrever Documentação

## 1. Introdução
<br>
Escrever documentação se refere ao processo de escrever um conjunto de artigos técnicos que instruem o usuário ao utilizar o produto. Uma documentação bem-escrita deve guiar o usuário de novato a expert no uso da ferramenta.
<br>
A documentação também será o primeiro lugar aonde seus usuários irão para qualquer dúvida ou problema que tiverem. Portanto, é importante garantir não só que seus usuários possam encontrar facilmente as respostas que procuram, mas também que estas sejam claras e completas. Idealmente, nenhum usuário irá visitar a mesma página duas vezes.

A documentação pode ser dividida em dois tipos:
- Referencias técnicas: estas páginas tem o dever de introduzir uma funcionalidade do produto e detalhar todas as suas características, como parâmetros, formas de uso, resultados, e erros conhecidos.
- Tutorias e guias: o objetivo destas páginas é de treinar o usuário no uso do produto. Elas consistem de uma série de passos que irão guiar o usuário na resolução de um problema, de forma que ao final dele, o usuário estará mais capacitado para usar a ferramenta de forma independente.

Documentação de sucesso irá utilizar ambos os tipos. 


## 2. Ator ferramentas e etc.
<br>
Escrever documentação é responsabilidade do **produtor de conteúdo** devido a sua habilidade de escrever de forma que engaje seus devs, com auxílio opcional do  **advogado**, que irá fazer a comunicação com o time de desenvolvimento para compreensão da ferramenta.
<br>
Sua documentação deve ser hospedada no mesmo local onde seu produto está disponibilizado. Se você tem uma webpage para seu produto, é lá que  seus usuários irão procurar a documentação. Se seu produto é acessado através de um repositório no GitHub, então é lá que ela deve ser encontrada.
<br>
Ferramentas:
<br>
O processo de escrever documentação se dará em três momentos:
- Na primeira release do produto, quando nenhuma documentação existe e deve ser criada do zero englobando todo o produto.
- A cada release subsequente do produto, de forma a adicionar referencias para as novas funcionalidades, e atualizar as páginas referentes a qualquer funcionalidade que foi modificada.
- Periodicamente, em resposta a feedback de usuários ou da análise de métricas, para melhorar a documentação existente.

## 3. Processos e diretrizes

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

  <input type="checkbox" name="uchk">
  <label for="uchk">Unchecked.</label>
  
- [ ] Você tem uma noção básica do produto, suas funcionalidades e seu propósito?

- [ ] Você possui uma lista indicando todas as funcionalidades do produto de forma completa?

- [ ] Essa lista está organizada de forma a refletir a estrutura do produto

- [ ] Você saberia explicar, um por um, o funcionamento de todos os elementos dessa lista?

- [ ] Você anotou todos os erros conhecidos, seus códigos, mensagens, efeitos e soluções?

- [ ] Você esteve em contato com o time de desenvolvimento para averiguar a completude de sua lista?

### 5.2. Fazer investigação empática do produto

- [ ] Você consegue identificar as razões pelas quais alguém usaria seu produto, e o que tentariam fazer com ele?

- [ ] Você tentou reproduzir esse processo hipotético?

- [ ] Você anotou suas experiências ao usar o produto? O que foi bom, o que foi ruim, o que foi prazeroso, o que foi difícil de entender?

- [ ] Você saberia, com assistência do time de desenvolvimento, guiar um novo usuário tentando fazer a mesma coisa de forma que ele não tivesse os mesmos problemas que você?

### 5.3. Organizar documentação

- [ ] Você possui uma lista de atividades que irá detalhar por meio de guias e tutoriais?

- [ ] Esta lista está separada por processo ou de outra forma intuitiva?

- [ ] Esta lista está ordenada de forma a refletir o uso natural do seu produto?

- [ ] O seu repositório de documentação está organizado da mesma forma?

- [ ] Você possui, no seu repositório, uma seção para armazenar as referências técnicas?

- [ ] Esta seção está subdividida e ordenada de forma a refletir a estrutura do seu produto?


### 5.4. Escrever documentação

- [ ] Você deu ao seu documento um título claro e instrutivo?

- [ ] No título, você usou uma ou mais palavras-chaves pelas quais o seu documento pode ser facilmente buscado e encontrado?

- [ ] Seu documento está subdividido por meio de cabeçalhos também claros e instrutivos?

- [ ] Seu texto pode ser compreendido por leitores de diferentes níveis de conhecimento técnico?

- [ ] Seu texto está livre de erros ortográficos e gramaticais?

- [ ] Seu texto está livre de gírias e regionalismo?

- [ ] Seu texto está livre de frases demasiado longas?

- [ ] Seu texto está livre da voz passiva?

- [ ] Seu texto está focado no objetivo, sem se alongar sobre assuntos tangenciais?

- [ ] Seu texto está livre de informação duplicada em alguma outra página?

- [ ] Seu texto possui imagens e diagramas ilustrativos?

- [ ] Estas imagens possuem legenda?

- [ ] Sua página possui links para outras páginas de conteúdo similar ou relacionado?

- [ ] Sua página possui etiquetas que facilitarão sua busca?

- [ ] Sua página mostra a data em que foi escrita ou atualizada?

- [ ] Sua página pode ser curtida ou comentada?

**Escrever tutoriais**

- [ ] Seu tutorial cobre o processo ao que se refere do início ao fim?

- [ ] Sue tutorial passa pelo maior número de funcionalidades possível, priorizando as mais importantes?

- [ ] Seu tutorial pode ser seguido da mesma forma por usuários em diferentes sistemas operacionais?

- [ ] Seu tutorial está detalhado de forma a impedir erros de interpretação?

- [ ] Cada passo do seu tutorial tem um resultado visível?

**Escrever guias**

- [ ] Seu guia está focado em uma atividade concreta?

- [ ] Seu guia pode ser seguido da mesma forma por usuários em diferentes sistemas operacionais?

- [ ] Seu guia está detalhado de forma a impedir erros de interpretação?


**Escrever referências**

- [ ] Sua referência detalha o funcionamento de dado aspecto do produto?

- [ ] Parâmetros de entrada?

- [ ] Possíveis configurações e opções?

- [ ] Forma correta de uso?

- [ ] Resultados?

- [ ] Erros conhecidos? (incluindo código, mensagem e solução recomendada)

**Escrever exemplos de código**

- [ ] Seu código está claro, e conciso, livre de mal práticas de código?

- [ ] Seu código pode ser copiado e colado sem afetar seu desempenho?

- [ ] Seu código está bem comentado?

- [ ] Seu código pode ser testado direto na página?


### 5.5. Revisar documentação

**Atualizar documentação**

- [ ] Existem funcionalidades completamente novas no novo release do produto?

- [ ] Estas novas funcionalidades foram documentadas seguindo os mesmos passos das primeiras?

- [ ] Alguma funcionalidade existente foi modificada?

- [ ] Todas as páginas que fazem referência a essa funcionalidade foram editadas para refletir seu estado atual?


**Corrigir documentação**

- [ ] Ao examinar as métricas de sucesso, ficou claro que alguma parte da documentação não está cumprindo seu papel?

- [ ] A documentação foi corrigida de forma a melhor alcançar seu objetivo?

**Criar lista de acesso rápido**

- [ ] Você criou e/ou atualizou uma lista de pelo menos cinco páginas que foram mais visitadas no último período, com links para as mesmas?

- [ ] Você criou uma lista similar para páginas recém-atualizadas?

### 5.6. Coletar métricas de sucesso

- [ ] Caso se aplique, você leu os comentários nas suas páginas?

- [ ] Caso se aplique, você verificou quantas curtidas relativas ao número de leitores recebeu cada página?

- [ ] Você verificou quantas pessoas visitaram cada página? Qual foi a mais vista e a menos vista?

- [ ] Você verificou quanto tempo, em média, os leitores se demoram em cada página?

- [ ] Você verificou quais páginas tendem a receber visitantes repetidos?

- [ ] Você verificou outros canais de feedback da comunidade (fóruns, tíquetes de suporte, etc.) para perceber se existem dúvidas frequentes que podem ser respondidas pela documentação?

- [ ] Você consegue extrair, de toda essa informação, alguma dica de como a sua documentação está falhando em atender as necessidades de seus usuários?


