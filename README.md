# number-3


Console.Writeline("Ge ett text");
string text=Console.Readline();

Console.Writeline("Det finns totalt "+text.Length+" indexer");

for(int x=0;x<=text.Length;x++)
{
    Console.Writeline("Index "+x+ " är " +text[x]);  
}

