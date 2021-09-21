# Conversor-de-moedas

function Converter() {
  var valorElemento = document.getElementById("valor");
  var valor = valorElemento.value;
  var valorEmDolarNumerico = parseFloat(valor);
  var valorEmReal = valorEmDolarNumerico * 5;
  console.log(valorEmReal);

  var elementoValorConvertido = document.getElementById("valorConvertido");
  var valorConvertido = " Resultado em Real é R$ " + valorEmReal;
  elementoValorConvertido.innerHTML = valorConvertido;
}

function Converter2() {
  var valorElemento2 = document.getElementById("valor2");
  var valor2 = valorElemento2.value;
  var valorEmDolarNumerico = parseFloat(valor2);
  var valorEmEuro = valorEmDolarNumerico * 6;
  console.log(valorEmEuro);

  var elementoValorConvertido2 = document.getElementById("valorConvertido");
  var valorConvertido2 = " Resultado em Euro é € " + valorEmEuro;
  elementoValorConvertido2.innerHTML = valorConvertido2;
}
