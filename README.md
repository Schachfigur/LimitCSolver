Teil der Bachelorarbeit: "Ein Löser für teilkorrekte Speicherbelegungsprotokolle in Programmieraufgaben"
Lukas Reinicke 
HS Mersburg

Erklärung Projekte:
LimitCProtokollInput 		-> 	Input Tool für Speicherbelegungsprotokolle
LimimtCSolver 			->	LimitCInterpreter
ProtokollResolver		-> 	Löser / Lösungsanwendung
ResolverCommonClasses		->	Klaasenbib für gemeinsam genutzt Klassen (Input + Resolver)

C# mit .NET6, Frontends WPF (Windows only)

Anwendung ist komplett mit Visual Studio 2022 Community Edition erstellt.

Zum bauen eines neues Parsers (nach Anpassung Grammatik) ist ANTLR4 notwendig!
Grammatik: \LimitCSolver\LimitC.g4
Generated Classes: \LimitCSolver\gen\

Verwendete Nuget-Packete:
CommunityToolkit.Mvvm (MIT)
Newtonsoft.Json (MIT)
Antlr4.Runtime.Standard (BSD 3-Clause)
