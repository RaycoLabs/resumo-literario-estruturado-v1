# 📚 Resumo Literário Estruturado v1

O **Resumo Literário Estruturado v1** é um prompt desenvolvido em **JSON** para orientar modelos de inteligência artificial na produção de resumos completos, organizados e fiéis a obras literárias.

A especificação estabelece regras detalhadas para a geração de textos objetivos e coesos, contemplando a contextualização da obra, os personagens principais, os conflitos, o desenvolvimento narrativo, o clímax, a resolução e o desfecho. Quando necessário para explicar integralmente a história, o prompt também autoriza a inclusão de spoilers.

O projeto tem como finalidade oferecer um padrão reutilizável, compatível com diferentes modelos de linguagem e capaz de manter consistência na estrutura e na qualidade dos resumos produzidos.

<a href="https://www.threads.com/@raylissonbr"><img src="https://img.shields.io/badge/Threads-@raylissonbr-green?style=flat-square" alt="Threads"></a>

---

## ✨ Principais recursos

* Especificação integralmente organizada em JSON.
* Estrutura narrativa composta por 12 a 18 parágrafos.
* Exigência mínima de 80 palavras por parágrafo.
* Linguagem formal, objetiva, clara e impessoal.
* Apresentação dos acontecimentos em sequência cronológica.
* Identificação dos personagens principais e de suas funções no enredo.
* Explicação completa do conflito central.
* Inclusão obrigatória do clímax e do desfecho.
* Permissão explícita para a apresentação de spoilers.
* Definição de critérios de qualidade e validação da resposta.
* Regras específicas para estilo, coesão, conectivos e progressão textual.
* Compatibilidade com diferentes modelos de inteligência artificial.

---

## 📂 Conteúdo definido pelo prompt

O arquivo `prompt.json` estabelece as regras necessárias para que o resumo apresente:

* a contextualização inicial da obra;
* o ambiente, o período e as circunstâncias relevantes da narrativa;
* os personagens principais;
* as relações existentes entre os personagens;
* o conflito central;
* os acontecimentos que desenvolvem o enredo;
* os conflitos secundários relevantes;
* o ponto de maior tensão da história;
* o clímax;
* a resolução dos principais conflitos;
* o desfecho completo;
* as consequências finais para os personagens;
* uma conclusão coerente com os acontecimentos narrados.

Além da organização do enredo, o prompt determina critérios relacionados à linguagem, à estrutura dos parágrafos, à fidelidade ao texto original, à progressão cronológica, aos conteúdos permitidos e proibidos e às validações necessárias para manter a consistência da resposta.

---

## 🎯 Objetivo

O principal objetivo deste projeto é padronizar a geração de resumos literários que:

* apresentem os acontecimentos essenciais da narrativa;
* preservem a ordem lógica e cronológica dos fatos;
* expliquem integralmente o enredo da obra;
* identifiquem adequadamente os personagens e seus papéis;
* descrevam o conflito central e seu desenvolvimento;
* incluam o clímax, a resolução e o desfecho;
* utilizem linguagem clara, formal e objetiva;
* evitem opiniões, julgamentos ou interpretações pessoais;
* mantenham fidelidade ao conteúdo original;
* ofereçam uma visão completa da história, mesmo quando isso exigir spoilers.

---

## ⭐ Recomendação de uso

Para obter resultados mais completos, consistentes e detalhados, recomenda-se utilizar o **GPT-5.6** com a configuração de inteligência definida no modo **Alto**.

Essa configuração é especialmente recomendada para obras extensas, narrativas com muitos personagens, estruturas não lineares, conflitos complexos ou enredos que exijam maior atenção à sequência dos acontecimentos.

A utilização do modo **Alto** não substitui a necessidade de fornecer corretamente o arquivo da obra e o conteúdo integral do `prompt.json`, mas pode contribuir para uma análise mais cuidadosa das instruções e para uma resposta mais fiel à estrutura solicitada.

---

## 💻 Compatibilidade

O prompt pode ser utilizado em modelos de linguagem capazes de interpretar instruções estruturadas em linguagem natural e em formato JSON, incluindo:

* ChatGPT;
* Claude;
* Gemini;
* DeepSeek;
* Qwen;
* Mistral;
* Llama;
* outros modelos equivalentes.

A qualidade do resultado pode variar conforme o modelo utilizado, o tamanho da janela de contexto, a extensão da obra e a capacidade do sistema de processar arquivos EPUB.

Para a melhor experiência, recomenda-se o uso do **GPT-5.6 com a inteligência configurada no modo Alto**.

---

## 🚀 Como utilizar

1. Abra o modelo de inteligência artificial de sua preferência.
2. Caso utilize o ChatGPT, selecione o **GPT-5.6**.
3. Configure a inteligência ou o nível de raciocínio no modo **Alto**.
4. Copie e envie o conteúdo completo do arquivo `prompt.json`.
5. Anexe o arquivo EPUB da obra que será resumida.
6. Solicite a geração do resumo com base nas regras fornecidas.
7. Verifique se a resposta atende aos critérios de estrutura, extensão e fidelidade definidos pelo prompt.

Exemplo de solicitação:

```text
Com base nas instruções do prompt fornecido, escreva um resumo completo da obra anexada.
```

Também é possível utilizar uma instrução mais detalhada:

```text
Leia a obra anexada e produza um resumo integral seguindo rigorosamente todas as regras definidas no arquivo prompt.json. Inclua os principais personagens, o conflito central, o desenvolvimento da narrativa, o clímax, a resolução e o desfecho completo.
```

---

## 📄 Formato esperado da saída

O resumo produzido deverá:

* ser apresentado em texto corrido;
* não utilizar títulos ou subtítulos internos;
* conter entre 12 e 18 parágrafos;
* apresentar no mínimo 80 palavras em cada parágrafo;
* contextualizar adequadamente a obra;
* identificar os personagens principais;
* explicar os acontecimentos essenciais da narrativa;
* respeitar a sequência lógica dos fatos;
* apresentar o conflito central e seu desenvolvimento;
* incluir o clímax;
* explicar a resolução dos conflitos;
* revelar o desfecho completo;
* incluir spoilers sempre que forem necessários para explicar a história;
* utilizar linguagem formal, objetiva, clara e impessoal;
* evitar opiniões, críticas e interpretações pessoais;
* manter fidelidade ao conteúdo da obra.

---

## 📚 Casos de uso

O **Resumo Literário Estruturado v1** pode ser utilizado em diferentes contextos, como:

* estudos literários;
* preparação para vestibulares;
* preparação para o ENEM;
* revisão de obras obrigatórias;
* criação de materiais educacionais;
* organização de bibliotecas digitais;
* catalogação de livros;
* produção de fichas de leitura;
* apoio a professores e estudantes;
* documentação de acervos literários;
* experimentos com inteligência artificial;
* estudos sobre engenharia de prompts;
* avaliação comparativa entre diferentes modelos de linguagem.

---

## ✅ Critérios de qualidade

Para que o resumo seja considerado adequado, a resposta deverá:

* cumprir a quantidade estabelecida de parágrafos;
* respeitar o número mínimo de palavras por parágrafo;
* apresentar os acontecimentos em ordem lógica;
* identificar corretamente os personagens;
* explicar o conflito central;
* incluir os eventos indispensáveis para a compreensão da narrativa;
* apresentar claramente o clímax;
* revelar a resolução e o desfecho;
* evitar informações inventadas;
* não contradizer o conteúdo da obra;
* manter uniformidade de linguagem e estilo;
* utilizar conectivos para garantir a continuidade entre os parágrafos;
* não substituir o resumo por uma análise, crítica ou interpretação literária.

---

## 🤖 Sobre o desenvolvimento

Este projeto foi desenvolvido com apoio significativo de ferramentas de inteligência artificial.

Parte da estrutura, da organização, do refinamento das regras e da documentação foi produzida com o auxílio do **GPT-5.6**, sendo posteriormente revisada, ajustada e validada pelo autor.

A proposta também demonstra como a colaboração entre desenvolvedores e sistemas de inteligência artificial pode contribuir para a criação de especificações detalhadas, reutilizáveis, organizadas e adaptáveis a diferentes modelos de linguagem.

Apesar do apoio da inteligência artificial, a revisão humana permanece essencial para verificar a clareza das instruções, corrigir inconsistências e garantir que o resultado final esteja alinhado aos objetivos do projeto.

---

## 🔎 Revisão e responsabilidade

Embora o prompt estabeleça regras detalhadas para melhorar a qualidade e a consistência dos resumos, modelos de inteligência artificial podem cometer erros, interpretar trechos de maneira inadequada, omitir acontecimentos importantes ou gerar informações que não estejam presentes na obra original.

Por esse motivo, recomenda-se revisar cuidadosamente todo o conteúdo produzido antes de utilizá-lo em trabalhos acadêmicos, materiais educacionais, publicações, avaliações ou sistemas de catalogação.

Sempre que possível, compare o resumo com a obra original e verifique especialmente:

* os nomes e as características dos personagens;
* a ordem cronológica dos acontecimentos;
* as relações entre os personagens;
* os conflitos apresentados;
* o clímax, a resolução e o desfecho;
* a presença de informações inventadas, imprecisas ou contraditórias;
* o cumprimento das regras estabelecidas no arquivo `prompt.json`.

A inteligência artificial deve ser utilizada como uma ferramenta de apoio, e não como uma fonte infalível. A responsabilidade pela conferência, pela correção e pelo uso final do conteúdo permanece com o usuário.

---

## ⚠️ Direitos autorais

Este repositório disponibiliza exclusivamente o prompt utilizado para orientar modelos de inteligência artificial na geração de resumos literários.

As obras utilizadas como entrada permanecem protegidas pelos direitos de seus respectivos autores, tradutores, ilustradores e editoras.

Utilize apenas arquivos que:

* estejam em domínio público;
* tenham sido adquiridos legalmente;
* possuam autorização de uso;
* possam ser processados de acordo com a legislação aplicável.

O usuário é responsável por respeitar a legislação de direitos autorais vigente em seu país e os termos de uso das plataformas empregadas.

O projeto não distribui livros, arquivos EPUB protegidos ou reproduções integrais de obras literárias.

---

## 🤝 Como contribuir

Sugestões, correções e melhorias são bem-vindas.

Caso identifique oportunidades para aprimorar a estrutura do prompt, aperfeiçoar as regras, ampliar a compatibilidade com outros modelos ou melhorar a documentação, você pode:

* abrir uma *Issue* descrevendo a sugestão ou o problema identificado;
* enviar um *Pull Request* com as alterações propostas;
* apresentar exemplos de resultados obtidos com diferentes modelos;
* sugerir novos critérios de validação;
* contribuir com melhorias de clareza, organização ou compatibilidade.

Antes de enviar uma contribuição, recomenda-se verificar se já existe uma discussão ou solicitação semelhante no repositório.

---

## 📄 Licença

Este projeto é distribuído sob a licença **MIT**.

Consulte o arquivo `LICENSE` para conhecer integralmente as condições de uso, modificação e distribuição.
