# Projeto-001
using System;

class MainClass {
  
  public static void Main (string[] args) {
    string produto1 = "Computador";
    string produto2 = "mesa de escritório";
    byte idade = 30;
    int codigo = 5290;
    char genero = 'M';
    double preco1 = 2100.0;
    double preco2 = 650.50;
    double medida = 53.234567;
    
    Console.WriteLine ("Produtos");
     Console.WriteLine (produto1 + " ,cujo preço é " + preco1);
      Console.WriteLine (produto2 + " ,cujo preço é " +preco2)
      ;

       Console.WriteLine ($"\nRegistro : {idade} anos de idade, codigo {codigo} e genero {genero}");

        Console.WriteLine ($"\nmedida com oito casas decimais : {medida}");
         Console.WriteLine ("Arredondando(tres casas decimais):  "+medida.ToString("F3"));
         Console.WriteLine ("separador decimal utilizando ponto: "+ medida.ToString("F3"));
          
    
  }
}
