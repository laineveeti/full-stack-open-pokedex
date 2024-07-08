Exercise 11.1
Veeti Laine

Here I will explore some options for building a CI/CD system for a small Python application.

Potential linting tools include flake8, Pylint, and Black. Libraries for unit testing include the standard Python unit testing library, pytest, and others. With pytest, the pytest-cov extension can be used to assess code coverage of the unit tests. For building and packaging,

Alternative self-hosted CI servers include Atlassian Bamboo and, while alternative cloud-based platforms include Gitlab, Azure Pipelines, CircleCI, and Bitbucket Pipelines.

A self-hosted CI environment may be needed if there is need to test the application on hardware for which cloud-based platforms do not provide options, or if more specialized computing is required. However, for a standard web application which does not involve any complex testing procedures, the cloud-based options are just fine.
