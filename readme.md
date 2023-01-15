
# First MicroTask
#### It is an API used to find the entire information about any user on CodeForces. It can also be used to fetch the entire description of the rating changes of an user during a particular contest.
## API Reference

#### Get item

```http
  GET https://5u3m9w.deta.dev/api/get-user-info/userid
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `userid` | `string` | **Required**. The user who's details we want to fetch |



Takes the user id and returns a list of User objects for requested handle.

#### Get item

```http
  GET https://5u3m9w.deta.dev/api/get-user-contests/userid
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `userid` | `string` | **Required**. The user who's details we want to fetch |



Takes the user id and returns a list of RatingChange objects for requested user.

### Installation

```bash
  git clone https://github.com/BattleOoze25/CodeForcesAPI
```
### Navigation
```bash
  cd CodeForcesAPI
```

### Installation

```bash
  npm i
```


### Run Server

```bash
  npm start
```

# Second Microtask
#### It is a microservice which consists of three microservice APIs :Authentication, ErrorHandler, and Visitor counter


## Installation

```bash
    git clone https://github.com/BattleOoze25/MicroTask2

```
### `Navigation`
```bash
    cd Microtask2
```
```bash
    cd AuthAPI or cd ErrorHandler or cd ViewCounter
```
### `Installation`



```bash
  npm i
```



### `Runserver`

```bash
  npm start
```


## API Reference
### ErrorHandler

#### Get a random error message which is handled by a dummy ErrorHandler middleware

```http
  GET http://localhost:3000/api/error
```



### Authentication

#### Sign-up(Returns token )

```http
  POST http://localhost:3000/api/sign-up
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `body` | `email` | **Required**|
| `body` | `password` | **Required**|


#### Log In(Returns token)

```http
  GET http://localhost:3000/api/sign-in
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `body` | `email` | **Required**|
| `body` | `password` | **Required**|

### ViewCounter
```http
  GET http://localhost:3000/api/get-visitors
```







# Third MicroTask
#### It is a microservice that takes the user's Latitude and Longitude as input and returns their  current address. It can also be used to get the Latitude and Longitude of a location by filling out the address.
## API Reference

#### Get item

```http
  GET https://z1jddk.deta.dev/get-address
```
Takes the user's location and returns their address


### Installation

```bash
  git clone https://github.com/BattleOoze25/GeoLocation
```
### Navigation
```bash
  cd GeoLocation
```

### Installation

```bash
  npm i
```


### Run Server

```bash
  npm start
```
## Author

- [@BattleOoze25](https://www.github.com/BattleOoze25)

