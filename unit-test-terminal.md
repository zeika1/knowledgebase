#create xunit:

`dotnet new xunit -o <name>`

#add references to xunit

`dotnet add test <foldername>/test*.csproj reference <projectfolder>/proj.csproj`

#run tests

`dotnet test <foldername>test*.csproj`
