# nome do projeto Info Sitedasala

##descrição 
1 - elaborado o wairframe no canva 
 ## Arquitetura 
 ## Estrutura do projeto 

/INFO2
|-Inicio 
essa página posos o acesso as outras páginas,uma logo da sala, um espaço para o mascote, mural de avisos onde é possivel publicar avisos.
um banner de saudação
mascote 
logo da sala 
acesso as paginas secundarias
painel de avisos, possibilidade de escrita de avisos
interação do mascote 

1. Visão Geral do Projeto  
O Info2 é um site colaborativo criado para a turma de 2026. Seu principal objetivo é atuar como um espaço centralizado que acompanha a rotina da turma, organiza os estudos, registra eventos importantes e preserva as memórias e histórias construídas pelos alunos.  

2. Estrutura de Navegação (Menu)  
O site conta com um menu acessível que organiza o conteúdo em seções temáticas:  
1. Início: Página de boas-vindas e apresentação da turma.  
2. Horário: Grade curricular e organização semanal das aulas.  
3. Matérias: Área para explorar categorias de aprendizagem e disciplinas.  
4. Museu: Espaço dedicado à história da turma, uniformes e lembranças.  
5. Professores: Seção para apresentar o corpo docente.  
6. Reportagens: Área para notícias e reportagens sobre a turma.  
7. Acesso: Área para identificação/login ou troca de status (ex: Visitante, Aluno).  

3. Detalhamento das Seções  
3.1. Página Inicial (Início)  
Apresentação: Mostra o título "Info2" e o subtítulo "Site da sala / Bem-vindos."  
Propósito: "Um lugar para acompanhar nossa turma, organizar os estudos e guardar as histórias que construímos juntos."  
Identificação de Status: Inclui tags visuais que mostram a sala, o ano (Sala · 2026) e o perfil de acesso atual (Visitante).  
Identidade Visual (Mascote): Exibe a arte oficial do mascote da turma, um lobo estilizado com detalhes em laranja e preto fazendo sinal positivo.  
Mural / Painel de Avisos:  
Uma seção interativa e editável para recados rápidos à turma. Possui um campo de texto "Escreva um aviso para a turma" e um botão "Publicar aviso."  

3.2. Organização: Horário (Horário)  
Estrutura: Planejado para mostrar "Uma semana de cada vez," acomodando até 9 aulas por dia, distribuídas em 5 dias.  
Legenda de Status:  
Células Preenchidas (matérias já cadastradas).  
Células Vazias (prontas para receber matérias com um toque para edição).  
Exemplo de Grade Atual:  
Segunda-feira: Matemática (1º horário), Práticas Experimentais (2º horário), Filosofia (3º horário).  
Terça-feira: Noções de robótica (1º horário), Cinema (2º horário), Cinema (3º horário).  

3.3. Aprendizagem: Matérias (Matérias)  
Visão Geral: Espaço para explorar as 21 categorias de estudo da turma, com nomes provisórios que podem ser mudados pelo editor.  
Exemplos cadastrados:  
01 / Σ Arte – Descrição: Danças brasileiras.  
02 / ◊ Biologia – Descrição: Ecologia.  

3.4. Memória: Museu do Info2 (Museu)  
Propósito: "Um espaço para guardar a história da turma, suas camisas e outras lembranças."  
Peça Principal (Uniformes):  
Mostra o modelo oficial da camisa da sala Info2 em uma única imagem, com detalhes de identificação do fornecedor Tamara Sports.  
Modelos de Camisa: Apresenta variações consideradas pela turma, como o Modelo I - Clássico (branco e dourado) e o Modelo II - Preto e Ouro.  
A História da Camisa (Relato Documentado):  
O Desafio Inicial: A busca por fornecedores foi complicada pelos preços altos. O aluno Murilo encontrou uma recomendação que viabilizou o projeto.  
Votações e Decisão: O processo exigiu várias votações e discussões até que o modelo ideal fosse escolhido.  
Logística e Antecipação (Outubro/Novembro de 2025): As camisas estavam prontas, mas havia um impasse sobre o prazo de entrega. Pagar R$ 20,00 extra garantiu a entrega na escola na sexta-feira (14 de novembro de 2025); a opção gratuita exigia esperar até segunda-feira (17 de novembro de 2025).  
Contribuição Coletiva: Para aproveitar as camisas mais cedo, Manu, Diego e Arthur decidiram contribuir financeiramente para antecipar a entrega, gerando agradecimento dos colegas.  
Outras Lembranças (Interclasse e Torcida):  
Organização da Torcida: Durante o interclasse, a turma criou um grupo para apoiar os jogadores.  
Ações de Apoio: Compraram isotônicos (Gatorades) para os atletas e providenciaram pompons, um tambor e uma música exclusiva da turma para animar os jogos.  
Filosofia da Turma: O registro lembra que, independentemente do resultado, o foco era a união, dedicação, espírito de equipe e apoio mútuo.  

4. Considerações Técnicas  
Plataforma de Criação: Desenvolvido e editado com ferramentas visuais dinâmicas, permitindo atualizações de texto, imagens e seções por editores autorizados.  
Design System: Paleta de cores escuras com contrastes em laranja e tipografia moderna, refletindo a identidade visual e o mascote da turma.  

3.5. Área Demonstrativa: Área dos Professores (05)  
Propósito e Aviso de Segurança:  
Seção para apresentar o corpo docente, atualmente configurada como um protótipo para demonstração.  
Aviso Crítico: O sistema avisa que o perfil não é verificado e proíbe o uso de notas reais ou dados pessoais nesta etapa.  
Estrutura de Cartões (7 Cartões · Duplique para adicionar):  
O layout usa um grid de 2 colunas com 7 cartões para fotos do corpo docente.  
Campos Editáveis por Cartão:  
Foto: Área demarcada para "Foto editável do professor ou da professora."  
Nome do professor: Campo para a inserção do nome.  
Matéria: Campo para vincular a disciplina.  
Ação: Botão laranja "Editar / salvar cartão" para confirmar as alterações.  
Integração de Acesso:  
Na base da página, há um bloco de "Acesso demonstrativo" com um botão que direciona o usuário para simular o login como Professor e testar o painel.  

3.6. Identificação: Acesso Demonstrativo (06)  
Propósito: Tela de simulação de entrada e seleção de nível de permissão.  
Funcionalidades e Campos:  
Navegação: Botão "← Voltar" no canto superior esquerdo para retornar à tela anterior.  
Nome ou usuário: Campo de texto para personalizar a sessão.  
Perfil demonstrativo: Menu suspenso para escolher o papel do usuário (ex.: Aluno, Professor).  
Ações de Entrada:  
Botão principal (laranja): "Entrar no protótipo."  
Botão secundário (escuro): "Acessar como visitante."  
Nota de Arquitetura / Segurança:  
O rodapé do formulário deixa claro que não há senha nem autenticação real no protótipo, recomendando a conexão com um sistema seguro antes de qualquer uso oficial.  

3.7. Reportagens (07)  
Propósito: Repositório dedicado a entrevistas, matérias e vídeos feitos pelos alunos da turma.  
Estrutura de Mídia:  
Projetado para conter três espaços independentes para vídeos da turma.  
Detalhamento do Bloco de Vídeo (Exemplo Vídeo 01):  
Player / Placeholder: Área superior aguardando a inserção de mídia.  
Título da Pauta: "Entrevista com o diretor Pedro" com espaço para o resumo quando disponível.  
Campos de Configuração:  
Link HTTPS do vídeo: Campo para inserir o vídeo hospedado externamente.  
Legenda: Campo para adicionar créditos ou descrição curta.  
Ação: Botão laranja "Assistir" que indica a abertura de um link externo.  

4. Resumo Geral da Arquitetura do Site (Mapa Completo)  
Para referência rápida, o fluxo completo do protótipo Info2 segue a numeração estrutural abaixo.

|-Acesso
é o local onde você realiza o login.
botão de voltar 
espaço para o nome
caixa de seleção
opção de acessar como visitante 

instalar as ferramentas utilizadas 
canva
visual studio code 
git 
github
prompt de comando 
google documentos
php 
msql
bootstrap,buma.io
navegador chrome,firefox,edge.
sistema operacional 
norma abnt 

instalar as depêndencias
rodar os programas necessarios

##Funcionalidade 
 permisão para usuário interno acessar o site 
 avatar interagindo
 painel de aviso
 acessar os videos 
 butão de voltar 
 acessar a pagina desejad acom um click
 na data 12 de novembro ficou confirmando que o video vai ser comprimido em svg
 o grupo de teste vai verificar se o esta antendendo toodos os requisitos vai fazer o deploy utilizando a hospedagem link nacional é o dominio eepddutra.com verificar se o site esta sendo responsivo no pc, no tablet, no celular.
 e verificar todas as funcionalidades.
##Licensa
mit 
 
