<script>
    function verificarResposta() {
      var respostaInserida = document.getElementById("resposta").value.toLowerCase();
      var respostaCorreta = "364462"; 

      if (respostaInserida === respostaCorreta) {
        window.location.href = "Enigma.htmll"; 
      } else {
        alert("tente novamente meu nobre.");
      }
    }

    function exibirDica() {
      var caixaDica = document.getElementById("caixaDica");
      caixaDica.style.display = "block";
      setTimeout(function() {
        caixaDica.style.display = "none";
      }, 5000);
    }
  </script>
</body>
