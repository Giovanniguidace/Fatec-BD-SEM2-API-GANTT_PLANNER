# Projeto Integrador 2º Semestre

## :orange_book: <b>Desafio do PI 1º Semestre:</b>

O desenvolvimento desse projeto partiu de uma demanda da empresa Necto, a partir de seu CEO Carlos Eduardo, que era de uma ferramenta que fosse fácil de mexer, que fosse portátil e ao mesmo tempo flexível para auxiliar no planejamento de seus projetos. Manipular um gráfico de Gantt afim de conquistar esses objetivos será o cerne do projeto. Outro fator decisivo para o desenvolvimento é a limitação que outras ferramentas semelhantes à do nosso projeto que impossibilitam ou dificultam muito a visualização da empresa como um todo, afim de conseguir conciliar o desenvolvimento de vários projetos simultaneamente com a distribuição da equipe da melhor forma possível, além de ter uma melhor distribuição dos recursos financeiros.

Para equipes que trabalham em múltiplos projetos e tarefas, que estão insatisfeitas com a dificuldade de fazer um planejamento com as ferramentas de planejamento disponíveis, o Gantt Planner é uma ferramenta visual de planejamento que auxilia o desenvolvimento do seu planejamento, minimizando os riscos de má distribuição de mão de obra, perder prazos e compreensão da evolução das tarefas. Ao contrário de outras ferramentas de planejamento conhecidas, nosso projeto oferece gráficos e relatórios completos e agradáveis com a possibilidade de compartilhamento do gráfico do planejamento como imagem para o time.

# <b>:dart: Objetivo da Aplicação Gantt Planner:</b>

Para que seja criada uma aplicação que atenda os requisitos solicitados pelo cliente, foram levantadas as seguintes necessidades:

* Cadastro de Pessoa:
	* Foi realizada a implementação do cadastro de pessoa para que o cliente pudesse inclui-lo nas tarefas e projetos, que posteriormente seriam visualizados no gráfico de GANTT. O cadastro de pessoas consiste em informações básicas de um funcionário e também com a possibilidade de classificá-lo com uma função do projeto ou o cargo que ele possui.
	
* Cadastro de Tarefa:
	* Foi realizada a implementação do cadastro de tarefa com a finalidade de inserir pessoas que serão contribuintes desta tarefa que pertencerá a um projeto. A tarefa possui as informações como descrição da tarefa, data de conclusão, pessoas que farão parte e qual o projeto que ela pertence.

* Cadastro de projeto:
	* Foi realizada a implementação do cadastro de projeto, onde ele terá as tarefas vinculadas a ele e nessas tarefas quem serão os executores. Desta forma, é possível jogar todas as informações necessárias para gerar o gráfico do GANTT.

* Cadastro de distribuição de tarefas:
	* Foi realizada a implementação do cadastro de distribuição de tarefas as pessoas, onde torna possível vincular uma tarefa a uma pessoa que fará parte do projeto.

* Relatórios:
	* Foi realizada a implementação de relatórios que torna possível a visualização do andamento do projeto, as tarefas que estão vinculadas a ele e as pessoas que estão vinculadas a esta tarefa. Também é possível visualizar datas de conclusão de cada tarefa.

Com a implementação destas funcionalidades em nosso projeto, foi possível disponibilizar ao cliente uma aplicação capaz de organizar projetos de desenvolvimento, dividido em tarefas e pessoas, com data de conclusão e uma prévia de conclusão de projeto.

### Compatibilidade entre o aplicativo e o mundo real

1.  A preocupação com o uso de ícones para as principais tarefas gera uma aproximação com o mundo real, trazendo um conforto propiciado pelo natural reconhecimento dos símbolos presentes no dia a dia.
2.  O mapa centralizado na tela do usuário em referência as televisões que ficam no centro da sala.

![real-virtual](https://gitlab.com/felipemessibraga/pi-phpython/uploads/3586344651689c3fc8d25e4227eae595/real-virtual.JPG)
### Controle e liberdade para o usuário

1.  O usuário pode navegar entre as versões do projeto, podendo voltar a uma versão anterior caso a atual não o agrade;
2.  É possível modificar quase todos os atributos dos projetos, tarefas e pessoas;
3.  O sistema é responsivo, para se adaptar aos diversos monitores e dispositivos;

### Consistência e padronização

1.  Os menus respeitam o mesmo padrão de design;
2.  Os icones apresentam apenas dois tipos, que variam apenas para evidenciar o seu contexto;

### Prevenção de erros

1.  Existe uma preocupação grande com a prevenção de erros. Todas as decisões que não podem ser desfeitas emitem uma confirmação;
2.  Os botões respeitam um margem mínima para que não haja cliques "sem querer".

![botoes](https://gitlab.com/felipemessibraga/pi-phpython/uploads/c2e675a3dbf8fbcab70ccadc283f9cf2/botoes.JPG)

### Eficiência e flexibilidade de uso

1.  O aplicativo foi pensado para que qualquer pessoa consiga utiliza-lo, por isso apresenta botões com objetivos claros, drag and drop para facilitar a movimentação das tarefas e contraste visual.
2.  Semelhança na disposição dos menus com ferramentas de uso popular como o Microsoft World;

### Estética e design minimalista

1.  Deixamos apenas as principais informações em evidência, deixando o maior volume de informações para os relatórios, onde essas informações são idealmente dispostas de forma a não sobrecarregar o visual;
2.  Sem propagandas ou qualquer informação desnecessária.

![wireframe-minimalista](https://gitlab.com/felipemessibraga/pi-phpython/uploads/4de17b52b70036620bf3c0c01800b9a9/wireframe-minimalista.JPG)


### Caso de Uso:

![image](https://user-images.githubusercontent.com/62898187/141995859-b7d91504-1668-44ec-82d5-02f4d396ed9c.png)

### Apresentação Final para o Cliente

https://www.youtube.com/watch?v=sePaF3FJYkg



#

## ⚙️ <b>Tecnologias Adotadas na Solução:</b>

-   Python - Motivo: Foi realizada uma votação para a utilização da linguagem Python, pois pensamos em utilizar o framework Django;
-   PostgreSQL - Motivo: Foi realizada uma votação em que a escolha do banco de dados foi o PostgreSQL devido à todos do grupo já terem uma familiaridade com este SGBD;
-   HTML - Motivo: Utilização de Front-End na aplicação;
-   JavaScript e CSS - Motivo: Foi realizado o uso das linguagens Javascript e CSS para a criação do layout e requisições GET, POST, DELETE E PUT para o manuseio de dados vindo do BackEnd. Também foi utilizada a linguagem Javascript para se comunicar com a API do Frappe e utilizar o gráfico de Gantt;
-   Django (Framework Python) - Motivo: Foi escolhido framework Django devido a sua utilização no projeto anterior e por ter uma maior facilidade na criação de API's;
-   Maquina Virtual - Motivo: Foram realizadas implementações de código dentro de máquinas virtuais, onde era possível transportar para utilização em computadores da Fatec;
-   GitLab - Motivo: Foi realizada a escolha opr votação do repositório do Gitlab, pois foi este o repositóroio escolhido no projeto anterior;
-   Whats App - Motivo: Foi escolhido por votação a utilização da ferramenta de mensagem do Whatsapp para comunicação do grupo;
- Heroku - Motivo: Foi escolhido o Heroku como provedor de hospedagem da aplicação, onde foi possível apresentar a aplicação em servidor público;

## :wrench: <b>Contribuições individuais/pessoais</b>

* Criação de cadastros de Projetos, Tarefas, Pessoas, Distribuição de Pessoas em Tarefas

Exemplo de um GET em todos os projetos cadastrados - Javascript

```javascript
1 function getAllProjects(){  
2 xhrGetProjeto = new XMLHttpRequest();
3 json = '';
4 xhrGetProjeto.open('GET', URLGETPROJETOS, true);
5 xhrGetProjeto.onreadystatechange = function(){
6 if(xhrGetProjeto.readyState == 4){
7		 if(xhrGetProjeto.status == 200){
8		 json = (JSON.parse(xhrGetProjeto.responseText));
9		 }else if(xhrGetProjeto.status == 404){
10		 }
11	 } 
12	 add_prj_menu_esquerdo(json);
13	 }
14	 xhrGetProjeto.send();
15	}
```

Exemplo de cadastro de Projeto, utilizando o método POST - Javascript

```javascript
/*EXEMPLO DE MÉTODO POST PARA A CRIAÇÃO DE UM NOVO PROJETO*/

//UTILIZANDO O MÉTODO NATIVO DO JAVASCRIPT XMLHttpRequest
1 xhrPostProjeto = new XMLHttpRequest();
2 xhrPostProjeto.open("POST", URLGETPROJETOS, true);
3 xhrPostProjeto.setRequestHeader("Content-Type", "application/json;charset=UTF-8");
4 xhrPostProjeto.setRequestHeader("X-CSRFToken", csrftoken);
5 xhrPostProjeto.setRequestHeader("withCredentials", 'True');
6 xhrPostProjeto.onreadystatechange = function(){
7 if(xhrPostProjeto.readyState == 4){
8			 if(xhrPostProjeto.status == 201){
9			 getProjeto();
10			 carregaTabelaProjeto();
11			 if((json.length+1) > 1){
12			 habilitaRecuoCodProjeto();
13			 }  
14		 }
15	 }  
16 }
17 xhrPostProjeto.send(JSON.stringify({
18					 'prj_id': codProjeto,
19					 'prj_nome': nomeProjeto, 
20					 'prj_escopo': escopo, 
21					 'prj_datainicio': dt_inicio,
22					 'prj_prazoentrega': dt_prazo,
23					 'prj_color': cor,
24					 "prj_cost": custo,
25					 "prj_hrs_dev": horas_desen,
26					 "prj_progresso": progressoprojeto
27					 }));
```
Para a criação deste método foi bastante desafiador obter os conhecimentos necessários de requisições POST, GET, PUT e DELETE e também entender o funcionamento de API's.

* Conexão com API criada com Django Rest Framework;

Exemplo das URL's criadas
```javascript
1 //**CADASTRO DE PESSOAS*////
2 URLGETPESSOAS = 'http://localhost:8000/person/';
3 //**CADASTRO DE PROJETOS*////
4 URLGETPROJETOS = 'http://localhost:8000/project/';
5 //**CADASTRO DE TAREFAS*////
6 URLGETTAREFAS = 'http://localhost:8000/task/';
7 //**CADASTRO DE DISTRIBUICAO DE PESSOAS EM TAREFAS*////
8 URLGETDISTRIBUICAO = 'http://localhost:8000/distribute/';
9 //**CADASTRO DE HABILIDADES*////
10 URLGETHABILIDADES = 'http://localhost:8000/habilidades/';
11//**CADASTRO DE DISTRIBUICAO DE HABILIDADES*////
12 URLGETDISTRHABILIDADES = 'http://localhost:8000/distributehab/';
```
* Criação de gráfico GANTT com requisições GET e POST para a Lib do Frappe;

Function criada para carregar o Gráfico de Gantt, contendo todas as informações necessárias cadastradas na aplicação e coletadas através do método GET - Javascript

```javascript
1 recebe_projetoGantt = [];
2 recebe_tarefaGantt = []
3
4 function carregaGantt(jsonProjetosGantt, jsonTarefasGantt){
5  
6 vetor_gantt = [];
7 //VALIDA SE O JSON CONTENDO OS DADOS DE PROJETOS ESTÃO VAZIOS
8 if(jsonProjetosGantt != null){
9 recebe_projetoGantt = jsonProjetosGantt;
10 }
11 
12 //VALIDA SE O JSON CONTENDO OS DADOS DE PROJETOS ESTÃO VAZIOS
13 if(jsonTarefasGantt != null){
14 recebe_tarefaGantt = jsonTarefasGantt;
15 }
16  
17 // FUNÇÃO QUE REALIZARÁ A ANÁLISE DE PROJETOS QUE ESTÃO SELECIONADOS(CHECKED)
18 checked_project = [];
19 for(i=0;i<recebe_projetoGantt.length;i++){
20  
21 if(document.getElementById("cb_prj"+recebe_projetoGantt[i]['prj_id']+"").checked){
22 checked_project.push(recebe_projetoGantt[i]['prj_id']);
23 }
24 }
25  
26 vetor_preparaProjetos = [];
27 nomeInterdependencia = '';
28 if(recebe_projetoGantt != ''){
29	 if(recebe_tarefaGantt != ''){
30 
31		 for(i=0; i<recebe_projetoGantt.length;i++){
32			 for(y=0;y<checked_project.length;y++){
33					 if(checked_project[y] == recebe_projetoGantt[i]['prj_id']){
34  
35  
36						 for(x=0;x<recebe_tarefaGantt.length;x++){
37								 if(recebe_tarefaGantt[x]['trf_id'] == recebe_tarefaGantt[x]['trf_interdependencia']){
38								 nomeInterdependencia = recebe_tarefaGantt[x]['trf_name'];
39									 }
40							 if(recebe_tarefaGantt[x]['fk_prj_id'] == recebe_projetoGantt[i]['prj_id']){
41  
42								 linha = [recebe_tarefaGantt[x]['trf_id'],  recebe_tarefaGantt[x]['trf_name'],recebe_tarefaGantt[x]['trf_datainicial'], recebe_tarefaGantt[x]['trf_datafinal'], recebe_tarefaGantt[x]['trf_interdependencia'], recebe_tarefaGantt[x]['trf_progresso'], recebe_projetoGantt[i]['prj_color'] ];
43								 vetor_preparaProjetos.push(linha);
44								 }
45						 }
46				 }
47			 }
48		 }
49  
50 if(vetor_preparaProjetos != ''){
51 tasks = []; //CRIA VETOR PARA RECEBER JSON
52  
53 // REALIZA O ENVIO DOS DADOS DOS PROJETOS PARA A API PARA QUE SEJA RETORNADO OS PARÂMETROS NECESSÁRIOS PARA IMPLEMENTAR NO GRÁFICO
54 for(i = 0; i< vetor_preparaProjetos.length;i++){ //FAZ A VARREDURA NO VETOR PARA CRIAR JSON
55						 tasks.push({ //CARREGA O JSON COM AS INFORMAÇÕES NECESSÁRIAS PARA CARREGAR O GRÁFICO GANTT
56						 'id': 'Task'+vetor_preparaProjetos[i][0],
57						 'name': vetor_preparaProjetos[i][1],
58						 'start': vetor_preparaProjetos[i][2],
59						 'end': vetor_preparaProjetos[i][3],
60						 'dependencies': 'Task'+vetor_preparaProjetos[i][4],
61						 'progress': vetor_preparaProjetos[i][5], 
62						 'custom_class': 'tcolor-'+vetor_preparaProjetos[i][0] 
63					 });
64  
65 }
66 //console.log("TASKS: "+tasks+""); //TESTE DE INTEGRIDADE
67 gantt = new Gantt('#gantt', tasks, { 
68 on_click: function (task) {
69 console.log(task);
70 document.querySelector('style').innerHTML = '';
71  
72 cores_tarefas();
73 },
74 on_date_change: function(task, start, end) {
75 console.log(recebe_tarefaGantt)
76 console.log(task, start, end);
77 const trf_id = parseInt(task.id.replace("Task",""))
78 const tarefa = recebe_tarefaGantt.filter(_ => _.trf_id == trf_id)[0]
79 tarefa.trf_datainicial = start.toISOString().split("T")[0]
80 tarefa.trf_datafinal = end.toISOString().split("T")[0]
81 putAtualizaTarefa(tarefa)
82  
83 },
84 on_progress_change: function(task, progress) {
85 console.log(task, progress);
86 },
87 on_view_change: function(mode) {
88 console.log(mode);
89 },
90 custom_popup_html: function(task) {
91  
92 // the task object will contain the updated
93 // dates and progress value
94  
95 //const end_date = task._end.format('MMM D');
96 nome_pessoa_gantt = '';
97	 for(i=0;i<recebe_tarefaGantt.length;i++){
98					 if(task.name ==  recebe_tarefaGantt[i]['trf_name']){
99					 dt_final_tarefa = recebe_tarefaGantt[i]['trf_datafinal'];
100					 cod_tarefa_gantt = recebe_tarefaGantt[i]['trf_id'];
101					 for(x=0;x<recebe_distribuicaoGantt.length;x++){
102							 if(recebe_distribuicaoGantt[x]['fk_trf_id'] == cod_tarefa_gantt){
103							 cod_pessoa_gantt = recebe_distribuicaoGantt[x]['fk_pes_id'];
104					  
105									 for(y=0;y<recebe_pessoasGantt.length;y++){
106											 if(cod_pessoa_gantt == recebe_pessoasGantt[y]['pes_id']){
107											 nome_pessoa_gantt = recebe_pessoasGantt[y]['pes_nome'];
108											 }
109									 }
110						 }
111					 }
112					  
113 }
114 }
115 split_dt_final_tarefa = dt_final_tarefa.split('-');
116 reverse_dt_final_tarefa = split_dt_final_tarefa.reverse();
117 join_dt_final_tarefa = reverse_dt_final_tarefa.join('-');
118  
119  
120 return `
121 <div class="details-container">
122 <label>${task.name}</label>
123 <p>Expected to finish by ${join_dt_final_tarefa}</p>
124 <p>${task.progress}% completed!</p>
125 <p>Pessoa: ${nome_pessoa_gantt} </p>
126 </div>
127 `;
128 }
129 });
130  
131 cores_tarefas();
132  
133 }
134 }
135 }
136}
```

Para criar esta integração foi bastante dificultoso, pois foi necessário aprender como trabalhar
com envio de parâmetros para a API e entender como os dados eram retornados para assim serem
utilizados e inseridos no gráfico.

Em relação à troca de cores dos projetos também foi bastante dificultoso, pois foi necessário
compreender um pouco mais afundo sobre DOM e assim realizar a troca da cor diretamente na tag
div em HTML.


* Auxilio na escolha das tecnologias do projeto:

	*	Inicialmente, a ideia era a utilização de tecnologias em que já estavam sendo ministradas neste
determinado semestre, para que pudéssemos adquirir conhecimento e concluir o semestre com boas 
notas.
Pensamos também em trabalhar com tecnologias que são muito utilizadas no mercado, como: Criação 
de API's; Front-End moderno; SCRUM como metodologia ágil; Back-End com Django;


* Auxilio na criação de ideias do projeto:

	*	O auxilio na criação das ideias do projeto envolve não só pensar em tecnologias, envolve o plano
de negócio do cliente, envolve o que o cliente deseja em questão de agilidade na utilização, em 
como a aplicação vai favorecê-lo quando foi utilizá-la. Por isso, a ideia inicial do projeto é a 
etapa principal e requer muito cuidado e projeção. Não podemos idealizar algo que não atenda ou 
que seja algo muito ruim de utilização. A performance foi uma das principais ideias que foram 
levantadas.


* Auxilio na criação na documentação do projeto:

	*	Após a idealização do projeto, é necessário levantar a documentação que será feita de todo o
escopo do projeto, da arquitetura, dos processos. Devido a isso, criamos: Caso de Uso; Modelo
EER; Desenho da arquitetura do projeto; Burndown das sprints; Vídeos explicativos; Imagens
ilustrando as telas da aplicação;


## 🧠 <b>Aprendizados Efetivos</b>

* Aprendizado no que se trata uma API:

	*	Eu já havia feito Programação e Desenvolvimento de Sistemas em 2010 e quando comecei a estudar 
na Fatec, foi quando eu retornei aos estudos na área de programação. Com isso, mesmo com a minha
bagagem de experiência na área de Infra de Redes, o termo e o que é API foi algo bem complexo 
de entender e aplicar em prática. Foi algo muito divertido, envolvente e desafiador aplicar a
criação de API em nosso projeto.


* Aprendizado em trabalhar com requisições GET, PUT, POST e DELETE utilizando a linguagem Javascript:

	*	Após entender como era o funcionamento e como criava uma API no back-end, mais precisamente
utilizando o Django Rest Framework, criamos por meio do JavaScript as funções de requisições,
fazendo com que a gente conseguisse coletar, deletar, criar ou atualizar dados diretamente no 
banco de dados, utilizando credenciais de acesso da aplicação como segurança.
	
		Algumas das dificuldades que tive na criação da API, foi utilizá-la em servidores em nuvem, no qual foi necessário entender que era necessário utilizar parâmetros no cabeçalho para métodos de POST, DELETE E PUT para que a conexão fosse de fato estabelecida e confiável. Um exemplo desse cabeçalho em Javascript:
		
	![image](https://user-images.githubusercontent.com/62898187/139694311-3873a323-7f25-46ff-8aa6-a750737a0dd7.png)

	Com este cabeçalho configurado, foi possível hospedar a aplicação na nuvem e trabalhar normalmente.


* Aprendizado em HTML e CSS:

	*	Para quem nunca havia entrado no mundo de desenvolvimento Web, apenas Desktop, foi um desafio bem grande como era a criação de templates em HTML e utilizar CSS para dar estilo. Foi muito animador e muito prazeroso aprender sobre esse assunto e hoje eu utilizo muito para a criação de minhas aplicações profissionais e educacionais.

		Um dos desafios mais interessantes que eu enfrentei com o trabalho de desenvolver o Front-End, foi, sem dúvida, criar os projetos, inserir as tarefas nesse projeto e diferenciá-los com cores, para que fosse possível diferenciar um projeto do outro com uma maior facilidade. Um exemplo do código que foi utilizado para criar essa funcionalidade foi a função:

```javascript
1 function add_prj_menu_esquerdo(jsonprj){
2 document.getElementById("prj_cadastrados").innerHTML = ''; 
3 vetor_prjcadastrados = [];
4  
5 for(i = 0;i<json.length;i++){
6 /*CARREGA VETOR PARA CADASTRAR PROJETO NO MENU LATERAL ESQUERDO */
7 
8 //CRIA VALOR PARA ADICIONAR NA DIV "prj_cadastrados"
9 add_btn_prj_menu_esquerdo = [json[i]['prj_id'],"<div class='div_shadow' 
10 style='background-color:"+json[i]['prj_color']+"'><input id='cb_prj"+json[i]['prj_id']+"' 
11 type='checkbox' ><button id='btn_prj"+json[i]['prj_id']+"' 
12 onClick='expandeTrf(this.id);dadosProjeto(this.id);'class='btn_shadow0' style='background-
13 color:"+json[i]['prj_color']+"'>"+json[i]['prj_nome']+"</button></div> "];
14
15 //ADICIONA LINHA PARA CRIAÇÃO DO BTN DE PROJETO
16 vetor_prjcadastrados.push(add_btn_prj_menu_esquerdo);
17 ///////////////////
18 }
19 /*ENVIA PROJETO AO MENU LATERAL ESQUERDO*/
20
21 //ZERA DIV PARA NOVOS BUTTONS
22 document.getElementById("prj_cadastrados").innerHTML = ''; 
23
24 // VARREDURA DO VETOR CRIADO COM OS INSERTS PARA A DIV
25 for(i = 0; i<vetor_prjcadastrados.length;i++){ 
26	//ADICIONA OS INSERTS NA DIV 
27	 document.getElementById("prj_cadastrados").innerHTML +=  vetor_prjcadastrados[i][1];
28  //CRIA NOVA DIV PARA RECEBER TAREFAS CORRESPONDENTES AO PROJETO CRIADO
29	 novaDivTrf = document.createElement("div");
30  //NOME DA DIV PARA RECEBER AS TAREFAS
31	 novaDivTrf.id = "trf_cadastradas_prj"+vetor_prjcadastrados[i][0]+"";
32  //ADICIONA A DIV ABAIXO DO PROJETO CRIADO
33	 document.getElementById("prj_cadastrados").appendChild(novaDivTrf);
34 ////////////////////////////////// 
35 }
36  
37 //FUNÇÃO ABAIXO INSERE AS TAREFAS NO PROJETO SELECIONADO PASSANDO O JSON COMO PARÂMETRO
38 vetorTrfCadastrados(json, null); 
39 }	
```
Nesta etapa, é realizada a inserção das tarefas no projeto criado acima:
```javascript
1 /*EXPANDE TAREFAS MENU CENTRAL ESQUERDO*/
2 recebe_vetorprojeto = [];
3 recebe_vetortarefa = [];
4 ///FUNÇÃO ATRIBUÍDA PARA O BTN GRAVAR TAREFA
5 function vetorTrfCadastrados(vetor_projeto, vetor_tarefa){
6  vetor_trfcadastrados = [];
7  if(vetor_projeto != null){
8  recebe_vetorprojeto = vetor_projeto;
9  }
10 if(vetor_tarefa != null){
11 recebe_vetortarefa = vetor_tarefa;
12 }
13 if(recebe_vetorprojeto != '' && recebe_vetortarefa != ''){
14 for(i=0;i<recebe_vetorprojeto.length;i++){//VARREDURA NOS PROJETOS CADASTRADOS
15 recebeCodPrj = recebe_vetorprojeto[i]['prj_id'];  //SELECIONA O CODIGO DO PROJETO 
16 for(x=0; x<recebe_vetortarefa.length;x++){ //VARREDURA NAS TAREFAS CADASTRADAS
17 if(recebeCodPrj == recebe_vetortarefa[x]['fk_prj_id']){//VALIDA O CODIGO DO PROJETO DO CADASTRO DE PROJETO AO CODIGO DO PROJETO NO CADASTRO DE TAREFA E CRIA UM VETOR PARA INSERIR NA DIV CRIADA.
18  
19 codTrf = recebe_vetortarefa[x]['trf_id']; //CODIGO DA TAREFA - TABELA TAREFA
20  
21 recebeNomeTrf = recebe_vetortarefa[x]['trf_name']; //NOME DA TAREFA - TABELA TAREFA 
22 corProjeto = recebe_vetorprojeto[i]['prj_color']; //COR DO PROJETO - TABELA PROJETO 
23 add_btn_trf_menu_esquerdo = [recebeCodPrj,"<button id='btn_trf"+codTrf+"' onClick='dadosTarefa(this.id)' class='btn_shadow3' style='border-color:"+corProjeto+"'>"+recebeNomeTrf+"</button>"]; // CRIA LINHA PARA NOVOS BOTÕES DE TAREFAS, ABAIXO DO PROJETO CORRESPONDENTE
24  
25 vetor_trfcadastrados.push(add_btn_trf_menu_esquerdo);//ADICIONA NO VETOR AS TAREFAS CADASTRADAS E SEUS RESPECTIVOS BOTÕES, COM O ID DO PROJETO NO ÍNDICE 0 
26 } 
27 } 
28 }
29 //console.log(vetor_trfcadastrados);//VERIFICA INTEGRIDADE DO VETOR 
30 }
31 }	

```

Esta função expande o projeto criado, mostrando quais tarefas foram inseridas nele.
```javascript
1 ///FUNÇÃO ATRIBUÍDA PARA O BTN PROJETO NO MENU LATERAL ESQUERDO
2 function expandeTrf(nomeBtn){
3  
4  divideBtn = nomeBtn.substr(7);//REMOVE E DEIXA APENAS O NÚMERO DE IDENTIFICAÇÃO DO BOTÃO DE CADA TAREFA "btn_trf'num exemplo'"
5   
6  selecionaDiv = document.getElementById('trf_cadastradas_prj'+divideBtn+'').textContent;//SELECIONA A DIV DE CADA PROJETO E VERIFICA SE TEM CONTEÚDO DENTRO
7  if(selecionaDiv == ''){//CASO NÃO TENHA CONTEÚDO
8   
9  for(i=0;i<vetor_trfcadastrados.length;i++){//FAZ VARREDURA NOS BOTÕES DAS TAREFAS
10  
11  
12 if(divideBtn == vetor_trfcadastrados[i][0]){ //CASO O NÚMERO DE IDENTIFICAÇÃO DO BTN DA TAREFA SEJA IGUAL AO ID DE CADA PROJETO, É ADICIONADO O BOTÃO NA DIV CORRESPONDENTE
13  
14 document.getElementById('trf_cadastradas_prj'+divideBtn+'').innerHTML += vetor_trfcadastrados[i][1];//ADICIONA OS BOTÕES DAS TAREFAS NAS DIV'S DOS PROJETOS CORRESPONDENTES
15 } 
16 }
17 }else{
18 document.getElementById('trf_cadastradas_prj'+divideBtn+'').remove() //CASO TENHA CONTEÚDO NA DIV, ELE É ELIMINADO. ISSO FOI FEITO PARA CRIAR O RECUO.
19 add_prj_menu_esquerdo();//ADICIONA NOVAMENTE A DIV DO PROJETO
20 getAllProjects();
21 }
22 }
```
* Aprendizado em Django Rest Framework:

	*	Após entender o que era API e como uma API funcionava, era partir para a parte prática. Utilizamos o Django Rest Framework como Framework para a criação da API. Utilizamos como método de autenticação as credenciais de acesso da própria aplicação.

		O método de autenticação é configurado no arquivo settings.py do Django e a nossa configuração ficou da seguinte forma:
		![image](https://user-images.githubusercontent.com/62898187/139694944-7da04e01-480b-4467-a820-66e703fae2a2.png)

Com esta configuração, foi possível trabalhar tanto com autenticação da aplicação, quanto Token.

* Aprendizado em Models, Views e Templates do Django:

	*	O modelo MVC e MVT eram termos que eu ainda não conhecia que são termos do mundo de desenvolvimento de aplicações web. Ao estudar Django mais a fundo, descobri que é utilizado o modelo MVT, onde Model é utilizado para a criação de tabela em banco de dados, Views é utilizado para trabalhar com a "transmissão" e "recebimento" de dados com os templates (Front-End: HMTL; CSS; JS;)

* Aprendizado em implementação de dados do Django conectando ao banco de dados SQLite3:

	*	Foi entendido que o Django utiliza de drivers desenvolvidos em python para a conexão e administração do banco de dados através do Model do Django. Alguns deles seriam: Psycopg2; Pymongo; pyodbc; SqlLite;	
	![image](https://user-images.githubusercontent.com/62898187/139695726-cb2faff6-5c6b-4097-8c77-7db7df27ac90.png)
	Este é um exemplo de Connection String do Django para o SQLite3, no qual é criado um arquivo .sql na pasta do projeto.
 
		 ![image](https://user-images.githubusercontent.com/62898187/139696059-ee21c915-5fc4-43cd-9052-e2619ee98222.png)
Este é um exemplo de um model que foi criado em nosso projeto. O Django faz a conexão com o banco e cria automaticamente o model, com as colunas programadas de acordo com o que é passado no próprio model.

* Aprendizado no sistema operacional Linux com base Debian:

	*	Ao trabalhar com a linguagem Python e com o framework Django, entendi que era hora de desenvolver em ambiente Linux, no qual eu já era familiarizado por trabalhar com esse O.S. 

* Aprendizado em trabalhar em equipe utilizando a metodologia ágil SCRUM:
	
	* Como no projeto anterior, foi utilizado a metodologia SCRUM como metodologia ágil. Desta forma, conseguimos praticar ainda mais esta metodologia e aplicar novos conceitos. 
	
* Aprendizado em utilização de repositórios de código utilizando comandos do GIT:

	* Em todo o projeto, utilizamos do GitLab como repositório de arquivos. Com isso, praticamos ainda mais o seu uso e a sua aplicabilidade. 	

* Deploy Heroku:

	*	Para que pudéssemos publicar a nossa aplicação, utilizamos de uma plataforma gratuita Heroku, e que ainda temos ele de pé do servidor em nuvem: http://pi-gantt-planner.herokuapp.com

