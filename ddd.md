# DDD
- [What is DDD?](#what-is-ddd)
- [Why DDD is needed?](#why-ddd-is-needed)
- [What is aggregate in DDD?](#what-is-aggregate-in-ddd)
- [What is anemic domain model?](#what-is-anemic-domain-model)
- [What is the correct way for having relations between aggregates?](#what-is-the-correct-way-for-having-relations-between-aggregates)
- [How to update several aggregates during one transaction?](#how-to-update-several-aggregates-during-one-transaction)
- [What is event storming?](#what-is-event-storming)
- [How domain events are related to eventual consistency?](#how-domain-events-are-related-to-eventual-consistency)
- [What is the difference between domain events and event sourcing?](#what-is-the-difference-between-domain-events-and-event-sourcing)
- [What is CQRS?](#what-is-cqrs)
- [What is the best practice for validation in DDD?](#what-is-the-best-practice-for-validation-in-ddd)
- [What is the best practice for Value Object?](#what-is-the-best-practice-for-value-object)
- [Possible issues with using domain model with public getters/setters and empty constructor?](#possible-issues-with-using-domain-model-with-public-getterssetters-and-empty-constructor)
- [How to work with large domain models? Is it correct to have a lot of fields in domain model?](#how-to-work-with-large-domain-models-is-it-correct-to-have-a-lot-of-fields-in-domain-model)
- [How should be published integration events? Inside or outside transaction?](#how-should-be-published-integration-events-inside-or-outside-transaction)
- [How to define the reference between aggregates?](#how-to-define-the-reference-between-aggregates)
- [Where to put validation rule for value object?](#where-to-put-validation-rule-for-value-object)
- [Possible integration ways between modules?](#possible-integration-ways-between-modules)

## What is DDD?
###### Relative links:
- https://vaadin.com/learn/tutorials/ddd/strategic_domain_driven_design
- https://vaadin.com/learn/tutorials/ddd/tactical_domain_driven_design
- https://vaadin.com/learn/tutorials/ddd/ddd_and_hexagonal
- https://github.com/peholmst/DDDExample

## Why DDD is needed?
###### Relative links:
- https://simpleprogrammer.com/importance-domain-driven-design/

## What is aggregate in DDD?
###### Relative links:
- https://martinfowler.com/bliki/DDD_Aggregate.html

## What is anemic domain model?
###### Relative links:
- https://martinfowler.com/bliki/AnemicDomainModel.html
- https://thedomaindrivendesign.io/anemic-model/

## What is the correct way for having relations between aggregates?
###### Relative links:
- https://vaadin.com/learn/tutorials/ddd/tactical_domain_driven_design

## How to update several aggregates during one transaction?
###### Relative links:
- https://docs.microsoft.com/en-us/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/domain-events-design-implementation

## What is event storming?
###### Relative links:
- https://philippe.bourgau.net/how-to-use-event-storming-to-introduce-domain-driven-design/
- https://github.com/mariuszgil/awesome-eventstorming

## How domain events are related to eventual consistency?
###### Relative links:
- https://www.infoq.com/news/2015/09/domain-events-consistency/

## What is the difference between domain events and event sourcing?
###### Relative links:
- https://www.innoq.com/en/blog/domain-events-versus-event-sourcing/

## What is CQRS?
###### Relative links:
- https://docs.microsoft.com/en-us/azure/architecture/patterns/cqrs
- https://www.kamilgrzybek.com/design/simple-cqrs-implementation-with-raw-sql-and-ddd/
- https://dzone.com/articles/cqrs-understanding-from-first-principles
- https://stackoverflow.com/questions/24474859/what-is-the-difference-between-command-commandhandler-and-service


## What is the best practice for validation in DDD?
###### Relative links:
- https://docs.microsoft.com/en-us/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/domain-model-layer-validations
- http://gorodinski.com/blog/2012/05/19/validation-in-domain-driven-design-ddd/
- https://enterprisecraftsmanship.com/posts/always-valid-vs-not-always-valid-domain-model/
- https://enterprisecraftsmanship.com/posts/validation-and-ddd/
- https://danielwhittaker.me/2016/04/20/how-to-validate-commands-in-a-cqrs-application/
- https://enterprisecraftsmanship.com/posts/validate-commands-cqrs/
- http://www.kamilgrzybek.com/design/domain-model-validation/
- http://www.kamilgrzybek.com/design/rest-api-data-validation/

## What is the best practice for Value Object?
###### Relative links:
- https://dzone.com/articles/value-objects

## Possible issues with using domain model with public getters/setters and empty constructor?
###### Relative links:
- https://thedomaindrivendesign.io/anemic-model/

## How to work with large domain models? Is it correct to have a lot of fields in domain model?
###### Relative links:
- https://martinfowler.com/bliki/BoundedContext.html

## How should be published integration events? Inside or outside transaction?
###### Relative links:
- https://devblogs.microsoft.com/cesardelatorre/domain-events-vs-integration-events-in-domain-driven-design-and-microservices-architectures/

## How to define the reference between aggregates?
###### Relative links:
- https://www.informit.com/articles/article.aspx?p=2020371&seqNum=4

## Where to put validation rule for value object?
###### Relative links:
- https://builtwithdot.net/blog/where-do-i-put-my-business-rules-and-validation

## Possible integration ways between modules?
###### Relative links:
- https://www.kamilgrzybek.com/design/modular-monolith-integration-styles/
