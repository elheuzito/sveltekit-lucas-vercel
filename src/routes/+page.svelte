<script>
	import ElementoImagem from './ElementoImagem.svelte';
	const imagem1 = '$lib/images/github.svg'
	let visible = false;
	function minhaFuncao() {
	  visible = true;
	}
	setTimeout(minhaFuncao, 200);
	</script>
	
	<svelte:head>
		<title>Home</title>
		<meta name="description" content="Svelte demo app" />
	</svelte:head>
	<section>
		<div class='teste'>
			<hr>
			<h1 class='Main'> 🎓<br>Atividades Acadêmicas:</h1>
			<h2 class='texto'>    <strong>Lista de Algoritimos</strong></h2>
			
		<p>
				1. Numero Primo<br>
				2. Somatório<br>
				3. Fibonacci<br>
				4. Máximo divisor comum<br>
				5. Ordenação<br>
				6. Contagem<br>
		</p>
		<h2 class='texto'>    <strong>Linguagens utilizadas:</strong></h2>
		<ElementoImagem/>
			
		</div>
	</section>
	
	<style>
		section {
			display: flex;
			flex-direction: column;
			justify-content: center;
			align-items: center;
			flex: 0.5;	
		}
	
		h1 {
			width: 100%;
			color:rgb(247, 247, 247);
		}
		.teste {
			border-top: 1px solid rgb(37, 37, 37);
			background-color: rgb(154, 157, 160);
			padding: 45px;
			padding-top: 10px;
			border-radius: 20px;
			width: 500px;
			box-shadow: rgba(0, 0, 0, 0.19) 0px 10px 20px, rgba(0, 0, 0, 0.23) 0px 6px 6px;
		}
	
		.texto {
			border-left: 4px solid white;
			padding-left: 15px;
			margin-bottom: 7px;
			font-size: 1.3em;
		}
		hr{
			border:none;
			border-top: 2px solid white;
		}
		.Main{
			text-shadow: rgb(51, 51, 51) 0.1em 0.1em 0.5em;
			margin-bottom: 20px;
		}
	
	</style>
	