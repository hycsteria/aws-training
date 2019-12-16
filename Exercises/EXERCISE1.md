#  Exercice 1: Store the events happening in Madrid in the next 100 days

Services used: Lambda, DynamoDB, S3.

## Description

You shall call the api https://datos.madrid.es/egob/catalogo/206974-0-agenda-eventos-culturales-100.json every day at 8:00 (cloudwatch event), through a Lambda function and persist the obtained result both in S3,
in a json format and in DynamoDB (primary key field id, sort key dtstart).

## Tecnical Requirements

Every resource you create shall start with your username as prefix.
