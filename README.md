##Para essa atividade iremos simular a avaliação de um protótipo através das Heurísticas estudadas. Dessa forma o aluno deve:

- Criar, na ferramenta que desejar, um protótipo de tela para um cadastro de produtos. Para esse cadastro não tem uma finalidade definida e é livre de escolha do aluno, podendo ser, por exemplo: produtos de um supermercado, produtos de uma loja de confecção, entre outros; (Obs: enviar o print de tela)

- Escolha 3 Heurísticas e apresente como ela foi atendida dentro do seu protótipo. Por exemplo:
Visibilidade do estado do sistema: descreva como o seu protótipo “mantém os usuários informados sobre o que está acontecendo por meio de feedback adequado e no tempo certo”?

##Heurísticas aplicadas:

###Reconhecimento em vez de Lembrança:
As categorias são apresentadas como botões visuais com ícone em vez de um campo de texto para o usuário memorizar e digitar, os campos de fornecedores e temporadas usam selects com opções pré-definidas, assim o usuário escolhe da lista em vez de tentar lembrar os nomes cadastrados, e também alguns campos possuem textos explicativos com exemplos de como deve ser preenchido.

###Visibilidade do Estado do Sistema:
Com barra de progresso no topo cresce conforme os campos obrigatórios são preenchidos, indicador de etapas com marcação visual de concluído/ativo/pendente, o campo Margem de lucro é calculado automaticamente e muda de cor: verde (saudável), amarelo (baixa) ou vermelho (negativa), o status do estoque aparece em tempo real: "Sem estoque" (vermelho), "Estoque baixo" (amarelo) ou "Disponível" (verde) e ao salvar, o botão exibe um spinner de carregamento e depois um toast de sucesso.

###Prevenção de Erros:
	Cada campo valida em tempo real durante a digitação, com mensagens de erro específicas (ex: "Preço de venda abaixo do custo!"), na tela de revisão, ao clicar em Salvar, o sistema verifica todos os campos obrigatórios e lista os erros antes de prosseguir e por fim um modal de confirmação exibe um resumo do produto para o usuário revisar antes da ação final ser executada.
