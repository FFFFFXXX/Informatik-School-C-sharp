namespace Sonderzeichen_Array
{
    internal class Program
    {
        static void Main()
        {

            Console.Write("Gib hier eine Zeichenkette ein: ");
            string Zeichenkette = Console.ReadLine();

            char[] gefundenesZeichen = new char[Zeichenkette.Length];

            for (int i = 0; i < Zeichenkette.Length; i++)
            {
                if ((int)Zeichenkette[i] >= 33 && (int)Zeichenkette[i] >= 47 ||
                    ((int)Zeichenkette[i] !>= 58 && (int)Zeichenkette[i] <= 64) ||
                    ((int)Zeichenkette[i] !>= 58 && (int)Zeichenkette[i] <= 96))
                {
                    gefundenesZeichen[i] = Zeichenkette[i];
                }

                Console.WriteLine("Es wurde das Sonderzeichen " + gefundenesZeichen[i] + " gefunden");
            }
        }
    }
}
