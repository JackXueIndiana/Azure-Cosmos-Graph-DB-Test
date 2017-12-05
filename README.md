# Azure-Cosmos-Graph-DB-Test
Based on this tutorial (https://docs.microsoft.com/en-us/azure/cosmos-db/create-graph-dotnet) I am trying to rerun the sample code in my subscription. In the process what I found are
1. This API needs net461, whcih is a default in Vistual Studio 2017
2. You need not only load in NuGet packages of Microsoft.Graph but also Microsoft.Graphs which is still in prerelease.
3. All the Gremlin queries you ran in code you can also run them in Cosmos Graph DB Data Explorer with graph presentation.
