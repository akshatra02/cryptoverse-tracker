
# Cryptoverse-Tracker
 Cryptoverse app helps you to fetch the price and fluctutaion of trending cryptocurrency!


## API Reference

#### Get all items

```http
  GET `https://api.coingecko.com/api/v3/coins/markets?vs_currency=${currency}&order=market_cap_desc&per_page=100&page=1&sparkline=false`
```

| Parameter |  Description                |
| :-------- |  :------------------------- |
| `Coin-list` |  To tabulate the coins |

#### Get item

```http
  GET `https://api.coingecko.com/api/v3/coins/${id}`
```

| Parameter  | Description                       |
| :--------  | :-------------------------------- |
| `Coin`     |Information of single Coin |

```http
  GET `https://api.coingecko.com/api/v3/coins/${id}`
```


## Deployment

To deploy this project run

1.Clone this project

```bash
  git clone 
```

2.Open command prompt of the  path where the project is downloaded and Run the project
```bash
npm start
```
4.If project cannot be deployed in command prompt, open folder in Visual Studio Code.

5.Delete  package-lock.json and node modules if any.

6.Open terminal and Run
```bash
npm install  --legacy-peer-deps
```

```bash
npm start
```




## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)


## Find a bug?
If you found an issue or would like to submit an improvement to this project,please subit an issue using the issues tab above. 