# Simple-Money-Format
Simples Classe de Formatação de Money

Setup:

Em sua Main você deve adicionar o seguinte método:

public static String format(final double valor) {

final NumberFormat format = NumberFormat.getInstance(Locale.GERMAN);
format.setMaximumFractionDigits(1);
return format.format(valor);

}

Depois de adiciona-lo você só precisa copiar a Classe de MoneyFormat para o Projeto.

Modo de Uso da Formatação:

Você deve criar uma String para receber o valor Formatado.

String valor = MoneyFormat.format(Váriavel que quer formatar);

Após utilizar o MoneyFormat é só usar a variável String que foi criada.


