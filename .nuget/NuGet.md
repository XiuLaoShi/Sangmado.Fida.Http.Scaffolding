Commands
------------
nuget setApiKey xxx-xxx-xxxx-xxxx

nuget pack ..\Sangmado.Fida.Http.Scaffolding\Sangmado.Fida.Http.Scaffolding.csproj -IncludeReferencedProjects -Symbols -Build -Prop Configuration=Release -OutputDirectory ".\packages"

nuget push .\packages\Sangmado.Fida.Http.Scaffolding.1.0.0.0.nupkg

