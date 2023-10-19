<svelte:head>
	<title>About</title>
	<meta name="description" content="About this app" />
</svelte:head>

<div class="agrupador">
<div class="text-column">
	<h1 class='Branco'>Lista de Java</h1>

	<p class='Branco'>
		1. Número é primo: <br>
		Um número inteiro positivo n é primo se for divisível apenas por 1 e por n.
	</p>
	<pre>Ex: O numero 5 é primo</pre>
	<a href='https://replit.com/@MateusSouza51/TestePrimo'><button class="button-5"> Testar </button></a>


	<p class='Branco'>
		2. Somatório: <br>
		Soma de um conjunto de números.
	</p>
	<pre>Ex: O somátorio de [1,2,3] é 6</pre>
	<a href='https://replit.com/@MateusSouza51/Somatorio#Main.java'><button class="button-5"> Testar </button></a>

  <p class='Branco'>
		3. Fibonacci: <br>
		A sequência de Fibonacci é uma sequência de números naturais cujos termos são definidos a partir da soma entre seus dois termos antecessores.
	</p>
	<pre>Ex: Exemplos de Fibonacci [0 1 1 2 3 5 ... ]</pre>
	<a href='https://replit.com/@MateusSouza51/Fibonacci#Main.java'><button class="button-5"> Testar </button></a>
	<p class='Branco'>
		4. Maximo Divisor Comum (MDC): <br>
		O máximo divisor comum (MDC) é o maior número que divide dois ou mais números inteiros sem deixar resto.
	</p>
	<pre>Ex: Por exemplo, o MDC de 12 e 18 é 6 </pre>
	<a href='https://replit.com/@MateusSouza51/MDC#Main.java'><button class="button-5"> Testar </button></a>
  <p class='Branco'>
		5. Ordenação (MDC): <br>
		Quick Sort é um algoritmo eficiente de ordenação por divisão e conquista.
	</p>
	<pre>Ex: [ 0 5 3 4 3 2 7] ... [ 0 2 3 4 5 7] </pre>
	<a href='https://replit.com/@MateusSouza51/QuickSort#Main.java'><button class="button-5"> Testar </button></a>
  </div>
</div>

<style>
	.Branco{
		color:white;
	}
  
	.button-5 {
  align-items: center;
  background-clip: padding-box;
  background-color: #fa6400;
  border: 1px solid transparent;
  border-radius: .25rem;
  box-shadow: rgba(0, 0, 0, 0.02) 0 1px 3px 0;
  box-sizing: border-box;
  color: #fff;
  cursor: pointer;
  display: inline-flex;
  font-family: system-ui,-apple-system,system-ui,"Helvetica Neue",Helvetica,Arial,sans-serif;
  font-size: 16px;
  font-weight: 600;
  justify-content: center;
  line-height: 1.25;
  margin: 0;
  min-height: 3rem;
  padding: calc(.875rem - 1px) calc(1.5rem - 1px);
  position: relative;
  text-decoration: none;
  transition: all 250ms;
  user-select: none;
  -webkit-user-select: none;
  touch-action: manipulation;
  vertical-align: baseline;
  width: 120px;
}

.button-5:hover,
.button-5:focus {
  background-color: #fb8332;
  box-shadow: rgba(0, 0, 0, 0.1) 0 4px 12px;
}

.button-5:hover {
  transform: translateY(-1px);
}

.button-5:active {
  background-color: #c85000;
  box-shadow: rgba(0, 0, 0, .06) 0 2px 4px;
  transform: translateY(0);
}
.agrupador{
  background-color: rgba(144, 155, 167, 0.5);
  padding: 0px 0px 30px 0px;
  border-radius: 10px;
}
</style>