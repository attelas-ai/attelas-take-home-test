# Attelas Take Home Test

## Introduction
Your task is to build a web API that classifies text inputs into predefined categories using a large language model for instance, gpt-3.5-turbo. The API should have at least one endpoint /predict that accepts a POST request with a text input and predefined categories and returns the predicted categories. The /predict endpoint should accept an optional parameter 'multi'. When it is true, multiple categories could be returned.

With this exercise, you will build an ASP.NET Core Web API to provide that information.

The produced solution should:

* Build with the dotnet build command.
* Run with the dotnet run command and start the local, console instance of the Web API.
* Contain all the necessary tests runnable with the dotnet test command.
* Have a documented API showing available operations and the request/response models.
* During the development of the service, please include all the good practices that would normally be used.

## Dataset

| categories               | text                                                                                   |
|--------------------------|----------------------------------------------------------------------------------------|
| Positive,Informative     | I love sunny days and clear skies. The weather report says it will stay sunny all week.|
| Positive                 | The service was excellent and the staff was friendly.                                  |
| Positive,Informative     | This new phone model is fantastic! It has many great features.                         |
| Negative                 | I hate waiting in long lines.                                                          |
| Negative                 | The food was terrible and the place was dirty.                                         |
| Negative,Informative     | This phone battery drains too quickly. Users have reported frequent issues.            |
| Informative              | The book was about a detective solving mysteries.                                      |
| Informative              | He went to the store to buy some groceries.                                            |
| Informative              | The meeting is scheduled for tomorrow afternoon.                                       |

## Things We value
* Clean and well-structured code
* Tests

## Stretch Goals
* Containerise the app
* Add security measures and authentication
* Other endpoints to accomplish different tasks with LLMs
* Add a simple frontend
