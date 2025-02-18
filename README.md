<h1>Worker Management System</h1>

<h2>Descrição</h2>
<p>Este é um sistema simples de gerenciamento de trabalhadores, permitindo o cadastro de trabalhadores, contratos por hora e cálculo de renda mensal com base nos contratos associados.</p>

<h2>Estrutura do Projeto</h2>
<h3>Pacote: <code>entities</code></h3>
<ul>
    <li><strong>Department</strong>: Representa o departamento ao qual um trabalhador pertence.</li>
    <li><strong>HourContract</strong>: Representa um contrato de trabalho por hora, contendo a data do contrato, o valor por hora e a duração em horas.</li>
    <li><strong>Worker</strong>: Representa um trabalhador, contendo nome, nível, salário base, departamento e uma lista de contratos por hora.</li>
</ul>

<h3>Pacote: <code>entities.enums</code></h3>
<ul>
    <li><strong>WorkerLevel</strong>: Enumeração que define os níveis de um trabalhador (<code>JUNIOR</code>, <code>MID_LEVEL</code>, <code>SENIOR</code>).</li>
</ul>

<h3>Pacote: <code>application</code></h3>
<ul>
    <li><strong>Program</strong>: Classe principal que interage com o usuário via terminal, permitindo cadastrar trabalhadores, contratos e calcular a renda mensal de um trabalhador.</li>
</ul>

<h2>Como Executar o Projeto</h2>
<ol>
    <li>Certifique-se de ter o Java instalado (Java 8+).</li>
    <li>Clone ou baixe este repositório.</li>
    <li>Compile e execute a classe <code>Program.java</code>.</li>
</ol>

<h2>Funcionalidades</h2>
<ul>
    <li>Cadastro de um trabalhador (nome, nível, salário base, departamento).</li>
    <li>Adição de contratos por hora ao trabalhador.</li>
    <li>Cálculo de renda para um mês/ano especificado.</li>
</ul>

<h2>Autor</h2>
<p>Projeto desenvolvido para fins de estudo sobre orientação a objetos em Java.</p>
