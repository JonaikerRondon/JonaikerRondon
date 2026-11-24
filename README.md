void apresentar() {
  print("Ola, meu nome e Jonaiker e estou aprendendo Flutter");
}

void saudar(String nome) {
  print("Bom dia, $nome!");
}

int dobro(int numero) {
  return numero * 2;
}

double media(double n1, double n2) {
  return (n1 + n2) / 2;
}

String situacao(double nota) {
  if (nota >= 7) {
    return "Aprovado";
  } else {
    return "Reprovado";
  }
}

int somarLista(List<int> numeros) {
  int soma = 0;

  for (int numero in numeros) {
    soma += numero;
  }

  return soma;
}

void main() {
  apresentar();
  apresentar();
  apresentar();

  saudar("rossana");
  saudar("carlos");
  saudar("isaias");

  print(dobro(5));
  print(dobro(21));

  print(situacao(media(8, 6)));
  print(situacao(media(5, 6)));

  List<int> numeros = [3, 7, 10];

  print(somarLista(numeros));
}
