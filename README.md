<h1 align="center"> Estudo de Japonês com Flashcards Interativos ✨ </h1>
Visão Geral
Aprenda japonês de forma interativa com este sistema de flashcards! Focado em Hiragana, Katakana e vocabulário básico, este projeto foi desenvolvido no Google Colab com a ajuda de um agente de IA 🤖 criado a partir de aulas da Imersão Alura 📚, utilizando a API do Google Generative AI para criar opções de múltipla escolha e mensagens motivacionais super legais!

<h2> Funcionalidades </h2>
Flashcards Interativos: Estude Hiragana, Katakana e vocabulário (animais, verbos, cores).

Múltipla Escolha: Teste seus conhecimentos com opções geradas pela IA.

Mensagens Motivacionais: Receba incentivo personalizado após cada ciclo de estudo.

Fácil de Usar: Interface simples no Google Colab, com configuração mínima.

<h2>Como Usar</h2>
Pré-requisitos
Conta Google: Necessária para acessar o Google Colab.

API Key do Google: Requerida para usar o modelo Generativo do Google. Você precisa obter uma chave de API do Google e armazená-la como um segredo no Google Colab.

<h2>Configuração</h2>
Abra no Colab: Abra o código do projeto no Google Colab.

Adicione a API Key:

No Colab, vá para o menu à esquerda e clique no ícone de segredo (cadeado).

Crie um novo segredo com o nome GOOGLE_API_KEY e cole sua chave de API do Google.

Execute o Notebook: Execute as células do Colab para instalar as dependências e inicializar o ambiente.

<h2>Instruções</h2>
Execute as Células: Execute as células do notebook Colab. A primeira célula irá instalar as dependências e configurar a API. Você verá uma mensagem se a API Key for carregada com sucesso.

Escolha o Tópico: O programa irá pedir para você escolher um tópico de estudo (Hiragana, Katakana, etc.).

Defina o Número de Flashcards: Escolha quantos flashcards você quer revisar em cada sessão.

Estude!: O flashcard será exibido com opções de múltipla escolha. Digite o número da sua resposta.

Veja os Resultados: Após cada ciclo, você verá seu desempenho e uma mensagem motivacional.

<h2>Estrutura do Código</h2>

```
Configuração Inicial e Instalação:
Configura a API do Google e define os dados dos flashcards.
Funções do Flashcard:
Lógica principal para gerar flashcards, opções e mensagens.
Rodar um Ciclo de Estudo:
Função principal para executar um ciclo de estudos.
```

<h2>Dados dos Flashcards</h2>
Os dados dos flashcards estão organizados em dicionários Python:

hiragana_chart: Hiragana e suas romanizações.

katakana_chart: Katakana e suas romanizações.

vocab_animals: Vocabulário de animais.

vocab_verbs: Vocabulário de verbos.

vocab_colors: Vocabulário de cores.

Contribuição</h2>
Contribuições são bem-vindas! Se você tiver ideias para melhorar o projeto, como adicionar mais vocabulário, novos recursos ou otimizar o código, sinta-se à vontade para abrir uma issue ou enviar um pull request.
