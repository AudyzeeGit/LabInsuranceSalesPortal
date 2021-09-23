# LabInsuranceSalesPortal

This is an example of a very simplified insurance sales system made in a microservice architecture using:

.NET 5
Entity Framework Core
MediatR
Marten
Eureka
Ocelot
JWT Tokens
RestEase
RawRabbit
NHibernate
Polly
NEST (ElasticSearch client)
Dapper
DynamicExpresso
SignalR


#Business Case
We are going to build very simplified system for insurance agents to sell various kind of insurance products. Insurance agents will have to log in and system will present them with list of products they can sell. Agents will be able to view products and find a product appropriate for their customers. Then they can create an offer and system will calculate a price based on provided parameters.
Finally agent will be able to confirm the sale by converting offer to policy and printing pdf certificate.
Portal will also give them ability to search and view offer and policies.
Portal will also have some basic social network features like chat for agents.
Latest feature is a business dashboard that displays sales stats using ElasticSearch Aggregations and ChartJS.

