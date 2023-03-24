# dt096g-lab3
I laborationen nyttjades mallmekanismen för att implementera algoritmer i kompileringstid.
För C++ kallas konceptet mall-metaprogrammering.

Metaprogrammering är en referens till olika sätt ett program har kunskaper och kan manipulera sig självt.

För mall-metaprogrammering kan inga variabler ändra värde efter instans vilket gör rekursionsimplementeringar naturlig.

Fördelar med ett sådant koncept är bland annat generisk programmering och kompileringstidsoptimisering.

I C++11 introducerades `constexpr` som kan användas för att låta kompileraren exekvera kod utan mallanvändning.

I C++ kan samt `std::enable_if` användas för att definiera `std::enable_if::type` om ett villkor är sant.
Vid användning till en mall är ett sådant argument enbart giltig om typen är definierad.

