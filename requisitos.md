# Aplicativo de academia

## Objetivos
criar um site de academia que auxilie na organização da rotina do atleta\aluno, disponibilize acompanhar o progresso, definir metas, ver treinos e exercícios. ao abrir página de treinos, aparecer dashboard.
### Stack Tecnlógico
- Backend: PHP estruturado com sessões nativas
- Banco de dados: MySQL (PDO para segurança)
- Frontend: HTML5, PHP, CSS, Tailwind CSS

#### Regras de negócio (CORE)
Tratar senhas de usuários com hash bcript
O sistema deve ter uma página de históricos e manter sempre os logs de qualquer alteração feita por 
qualquer usuário, para auditorias futuras.
Insira suas regras de negocio.
- Efetuar login no sistema com Email.
1	Insere o Email	
2	Insere a senha 	
3	Cliente em entrar	
4		Abre a tela inicial 
- Gerenciando o atendimento ao cliente
Abrir sistema 	
	Exibir tela de inicio
Entrar em clientes 	
	Abrir tabela de todos os clientes cadastrados
Clicar em pagamentos 	
	Abrir ficha de valores e pagamentos mensais
Enviar pagamento ao Email do cliente	
- Gerenciamento de treinos
Personal oferece os treinos ao cliente/aluno, mostra os treinos e ensina a execução deles.	
	Realiza os treinos e registra a lista de treinos no aplicativo.
Avalia o treino e o desempenho do cliente/aluno e classifica o nível de treino.	
	Cliente/aluno registra seus resultados no aplicativo e conclui o treino.
- Finalização do treino
Registrou no aplicativo	
	Marca na diária como treino concluído e contabiliza.

##### Regras Globais
- Use sempre PDO para conexão e queries no MySQL para evitar SQL Injections
- Mantenha o código limpo e comente apenas logicas complexas.
- Separe os arquivos de forma lógica: um arquivo para conexão com a base (bd.php) e scripts de backend isolados e views em HTML5/PHP, nunca faça o sistema como um monolito, deixe sempre separados todas as regras para facilitar os futuros upgrades.
 - Estilize as telas em Tailwind de forma responsiva priorizando o MobileFrist.
 - Retorne sempre as mensagens de erros de forma claras na interface para o usuário (TOAST)
 - sempre trate as mensagens de caixa de mensagens nativas do navegador em um MODAL

