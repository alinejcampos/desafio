
{
             //Ela precisa de um programa que armazene alunos com suas matrículas e notas em uma "tabela" no final,
            //ela tem a necessidade de saber se o aluno foi aprovado ou não

            string nomeAluno;
            float matricula, nota1, nota2, media;

            Console.Write (" Nome do Aluno:"   );
            nomeAluno = Console.ReadLine();

            Console.Write(" Numero da Matricula:  ");
            matricula = float.Parse(Console.ReadLine());

            Console.Write(" Primeira nota com peso 2:  ");
            nota1 = float.Parse(Console.ReadLine());

            Console.Write(" Segunda nota com peso 8: ");
            nota2 = float.Parse(Console.ReadLine());

            media = (nota1 + nota2) / 2;

            if(media >=6)
            {
                Console.Write ("Aprovado");
            }
            else if (media >=4 && media <6)
            {
                Console.Write("Exame");
            }
            else
            {
                Console.Write("Reprovado");
            }
        }
    }
}
