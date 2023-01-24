
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

![1](https://user-images.githubusercontent.com/114417361/214316715-7e044eb3-599d-4d0b-a63b-30b940ead4b3.png)
![2](https://user-images.githubusercontent.com/114417361/214316742-2cfcf0d0-46d0-4561-bc86-7efc9d37bf90.png)
![3](https://user-images.githubusercontent.com/114417361/214316752-e2aae393-3cf5-420e-a1be-855c8c440ad7.png)
![4](https://user-images.githubusercontent.com/114417361/214316778-d026a30e-cb02-40ef-8f43-4fba48560f9b.png)



## Find a bug?
If you found an issue or would like to submit an improvement to this project,please subit an issue using the issues tab above. 
