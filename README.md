# number-3


Console.Writeline("Ge ett text");
string text=Console.Readline();

Console.Writeline("Det finns totalt "+text.Length+" indexer");

for(int i=0;i<=text.Length;i++)
{
    Console.Writeline("Index "+i+ "är" +text[i]);  
}

