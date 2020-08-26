# Cake Bakery

There are four companies.

Order -> Central company which takes orders for cake. (Coordinator)
Sugar, Cream, Bread -> Child companies (slaves)

It uses two-phase-commit protocol to ensure that wuantities are reduced from all the child companies while receiving an order in the parent company.

Front end of three of the applications are done in React js where as one compnay is developed using embedded javascript.
Backend of all the applications are developed using Node js and Express.

Deployment of Cream and Sugar companies are done using docker containers on openstack. Deployment of Sugar and cream companies are done using serverless technology lambda functions of AWS for backend and Amazon S3 bucket for frontend.
