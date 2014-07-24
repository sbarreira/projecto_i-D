projecto_i-D
============
isLetter- O método determina se o valor de char especificado é uma letra

public class isLetter {

   public static void main(String args[]) {
      System.out.println(Character.isLetter('c'));
      System.out.println(Character.isLetter('5'));
   }
}

isDigit - O método determina se o valor de char especificado é um dígito

público classe IsDigit {

   public static void main ( String args []) { 
      System . out . println ( Character . isDigit ( 'c' )); 
      System . out . println ( Character . isDigit ( '5' )); 
   } 
}

isWhitespace -  O método determina se o valor de char especificado é um espaço em branco, o que inclui espaço, tabulação ou nova linha.

público classe isWhitspace {

   public static void main ( String args []){ 
      System . out . println ( Character . isWhitespace ( 'c' )); 
      System . out . println ( Character . isWhitespace ( ' ' )); 
      System . out . println ( Character . isWhitespace ( '\n' )); 
      
   } 
}

isUpperCase - O método determina se o valor de char especificado é maiúscula

público classe isUppercase {

   public static void main ( Strin)); g args []){ 
      System . out . println ( Character . isUpperCase ( 'c' )); 
      System . out . println ( Character . isUpperCase ( 'C' 
      System . out . println ( Character . isUpperCase ( '\n' )); 
     
   } 
}

isLowerCase -

public class isLowercase {

   public static void main(String args[]){
      System.out.println(Character.isLowerCase('c'));
      System.out.println(Character.isLowerCase('C'));
      System.out.println(Character.isLowerCase('\n'));
     
}



// isLetterOrDigit - determina se o caractere especificado é uma letra ou um dígito;


import java.lang.*;

public class isletterordigit {

   public static void main(String[] args) {

      // criar primitivas char;

      ch1 = 'A';
      ch2 = '1';

      // criar primitivas boleanas;

    
      b1 = Character.isLetterOrDigit(ch1);
      b2 = Character.isLetterOrDigit(ch2);

      String str1 = ch1 + " é letra " + b1;
      String str2 = ch2 + " é digito " + b2;

      // imprimi os valores
      System.out.println( str1 );
      System.out.println( str2 );
   }
}

// isDefine - determina se um personagem é definido em Unicode;

import java.lang.*;

public class isdefine {

   public static void main(String[] args) {

      // criar primitivas char;

      
      ch = '@';

      // criar premitivas boleanas;

      
      b = Character.isDefined(ch);

      String str = "Character " +ch+ " has defined meaning in Unicode is " +b;

      
      System.out.println( str );
   }
}


// caso especial; 

// toString - O método retorna um objeto String representando o valor de caracteres especificado, ou seja, uma cadeia de um caractere;

public class Test { 

   public static void main ( String args []){ 
      System . out . println ( Character . toString ( 'c' )); 
      System . out . println ( Character . toString ( 'C' )); 
   } 
}

Função de converção

toUpperCase - O método retorna a forma maiúscula do char valor especificado
público classe Teste {

   public static void main ( String args []){ 
      System . out . println ( Character . toUpperCase ( 'c' )); 
      System . out . println ( Character . toUpperCase ( 'C' )); 
   } 
}

toLowerCase - O método retorna a forma minúscula do char valor especificado
public class Test{

   public static void main(String args[]){
      System.out.println(Character.toLowerCase('c'));
      System.out.println(Character.toLowerCase('C'));
   }
}
