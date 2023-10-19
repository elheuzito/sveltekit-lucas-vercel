<script>
    import java from '$lib/images/java.svg';
    import JavaScript from '$lib/images/JavaScript.svg';
  </script>
  
  <style>
    .container {
      display: grid;
      grid-template-columns: 1fr 1fr; /* Duas colunas com largura igual */
      gap: 8px; /* Espaço entre as imagens e subtítulos */
      text-align: center; /* Centralizar o texto */
      margin-top: 20px;
      margin-bottom: -20px;
    }
  
    .imagem {
      width: 65%; /* As imagens ocupam 100% da largura da coluna */
      border-radius: 15px;
      box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.3);
    }
  
    .subtitulo {
      font-weight: bold;
    }
  </style>
  
  <div class="container">
    <div>
      <img src={java} alt="Imagem 1" class="imagem">
      <p class="subtitulo">Java</p>
    </div>
    <div>
      <img src={JavaScript} alt="Imagem 2" class="imagem">
      <p class="subtitulo"><strong>Javascript</strong></p>
    </div>
  </div>