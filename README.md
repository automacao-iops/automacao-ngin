# automacao-ngin

<h2>Criação de Variáveis:</h2>
<p>
 • Padrão CamelCase<br/>
 • A variável deve ser autoexplicativa, ou seja, crie as variáveis de forma que ela faça referência exatamente a sua funcionalidade<br/>
   <p><b>EX:</b> variável que limpa cache - "limpaCache"

<h2>Criação de métodos:</h2>
<p>
	- Segue mesmo padrão para o item anterior.

<h2>Criação de Strings soltas:</h2>
	Quanto a necessidade de utilizar uma String, essa não deve ser inserida diretamente no código exceto quando extremamente necessário.<br/>
	Para criação de Strings soltas, existe a classe "RSCGlobalStrings"
<h2>Branch:</h2>
	Todo desenvolvimento deve ser realizado em branch local e o nome da branch deve seguir o seguinte padrão "prefixo_sufixo_nomedabranc", em letras minúsculas.<br/>
•	<b>Prefixo</b> =  Épico a que a atividade se destina, (ex: HADA = hada, ATLYS = atls, ORDEM = ordm, TV_BANDA_LARGA = tvbl );<br/>
•	<b>Sufixo</b> = Padrão para desenvolvimento (ex: dev);<br/>
•	<b>Nome da Branch:</b> Atividade que esta sendo desenvolvida (ex: "slotduplicado", portafxs).<br/>
<p>
	Para casos em que será aplicada uma correção, atualização ou melhoria acrescentar ao nome da branch os termos correspondentes a ação aplicada

•	<b>Correção</b> - hotfix;<br/>
•	<b>melhoria</b> - feature;<br/>
•	<b>Atualização</b> - codeup;<br/>
	<p><b>EX: </b>"pref_sufixo_nomedabranch/hotfix"

	Toda branch local sempre provem da branch developer do repositório remoto ao qual será direcionado o MR - Merge Request. Somente depois de passar por code review é que a branch "developer" do repositório remoto será mergiada para a "master"
