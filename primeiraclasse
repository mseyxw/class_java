class Livro {
    String nome, autor;
    int ano_lancamento, n_paginas, nota;
    boolean lido;
    
    void status(){
        System.out.println ("=====================================================================");
        System.out.println ("Nome:" + this.nome);
        System.out.println ("Autor:" + this.autor);
        System.out.println ("Ano de lançamento:" + this.ano_lancamento);
        System.out.println ("Número de páginas:" + this.n_paginas);
        System.out.println ("Foi lido?" + this.lido);
        System.out.println ("NOTA:" + this.nota);
    }
            
    void doacao() {
        if (lido == true) {
           System.out.println ("Você já leu esse livro, será se não está na hora de doá-lo?");
        }
        else {
           System.out.println ("Termine de ler o livro e depois doe para alguém que precisa.");
        }
    }
            
      void favoritos() {
        
        if (lido == true) {
        if (nota >= 4) {
           System.out.println ("Esse é um dos seus livros favoritos!");
        }
      }
        if (nota < 4) {
           System.out.println ("Esse não é um dos seus livros favoritos.");
        }
        System.out.println ("=====================================================================");
    }        
            
}

public class Main {

    public static void main(String[] args) {
        
      Livro L1 = new Livro ();
         L1.nome = "Pessoas normais";
         L1.autor = "Sally Rooney";
         L1.ano_lancamento = 2019;
         L1.n_paginas = 264;
         L1.lido = false;
         L1.status();
         L1.doacao();
         L1.favoritos();
       
      Livro L2 = new Livro ();
         L2.nome = "Novembro de 63";
         L2.autor = "Stephen King";
         L2.ano_lancamento = 2013;
         L2.n_paginas = 728;
         L2.lido = false;  
         L2.status();
         L2.doacao();
         L2.favoritos();
         
      Livro L3 = new Livro ();
         L3.nome = "Jantar Secreto";
         L3.autor = "Raphael Montes";
         L3.ano_lancamento = 2016;
         L3.n_paginas = 360;
         L3.nota = 4;
         L3.lido = true;
         L3.status();
         L3.doacao();
         L3.favoritos();
         
       Livro L4 = new Livro ();
         L4.nome = "Quinze dias";
         L4.autor = "Vitor Martins";
         L4.ano_lancamento = 2017;
         L4.n_paginas = 208;
         L4.lido = true;
         L4.nota = 3;
         L4.status();
         L4.doacao();
         L4.favoritos();
         
        Livro L5 = new Livro ();
         L5.nome = "A revoluÃ§Ã£o dos bichos";
         L5.autor = "George Orwell";
         L5.ano_lancamento = 2021;
         L5.n_paginas = 111;
         L5.lido = true;
         L5.nota = 5;
         L5.status();
         L5.doacao();
         L5.favoritos();
         
    }
}
