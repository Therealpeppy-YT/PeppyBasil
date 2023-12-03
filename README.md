// About Me

Console.WriteLine("I know a little bit of C# \nI'm also trying to learn some python too.");


Console.WriteLine("Did you know I have a youtube channel?");
string ytchnlAnswr = Convert.ToString( Console.ReadLine() );

switch(ytchnlAnswer)
{
case "Yes":
Console.WriteLine("Sick! but are you subbed though?);
string youSubbed = Convert.ToString( Console.ReadLine() );

switch(youSubbed)
{
    case "Yea":
    Console.WriteLine("Awesome! You're the best tysm")
    break;
    case "Nah":
    Console.WriteLine("Well go check it out then and maybe sub at youtube.com/@Therealpeppy");
    break;
}
break;

case default:
Console.WriteLine("Well go check it out then at youtube.com/@Therealpeppy");
break;
}

Console.WriteLine("Press any key to exit!")
Console.ReadKey();
