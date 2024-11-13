# Menu-Classe-Ordena
Em sala.

  private int a, b, c, aux;

  public int Organizar()
        {
            Console.Clear();
            Console.WriteLine("Insira 3 numeros na sequencia: ");
            a = Convert.ToInt32(Console.ReadLine());
            b = Convert.ToInt32(Console.ReadLine());
            c = Convert.ToInt32(Console.ReadLine());

  //ordenar os valores
            if (a > b) { aux = a; a = b; b = aux; }
            if (a > c) { aux = a; a = c; c = aux; }
            if (b > c) { aux = b; b = c; c = aux; }

  Console.WriteLine("Os numeros ordenados: " + a.ToString() + " " + b.ToString()
                 + " " + c.ToString());
            return 0;
        }
    }
}
