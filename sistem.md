# Class Diagram

## User

| Attribute             | Type       |
|-----------------------|------------|
| userID                | int        |
| name                  | String     |
| email                 | String     |
| isSubscriber          | boolean    |
| credits               | int        |
| rentedMovies          | List[Movie]|
| purchasedMovies       | List[Movie]|

## Movie

| Attribute             | Type       |
|-----------------------|------------|
| movieID               | int        |
| title                 | String     |
| genre                 | String     |
| releaseDate           | Date       |
| price                 | float      |
| rentalPrice           | float      |
| isAvailable           | boolean    |

## Subscription

| Attribute             | Type       |
|-----------------------|------------|
| subscriptionID        | int        |
| user                  | User       |
| startDate             | Date       |
| endDate               | Date       |

## CreditPurchase

| Attribute             | Type       |
|-----------------------|------------|
| purchaseID            | int        |
| user                  | User       |
| amount                | int        |
| purchaseDate          | Date       |

## MovieRequest

| Attribute             | Type       |
|-----------------------|------------|
| requestID             | int        |
| user                  | User       |
| movieTitle            | String     |
| requestDate           | Date       |
