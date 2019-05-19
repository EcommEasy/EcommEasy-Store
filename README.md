# Setup Instructions

## Requirements
   - Node.js >= 8
   - MongoDB >= 3.2
   
## EcommEasy Frontend (Store) Installation

- **Clone Git repository**
```shell
git clone https://github.com/EcommEasy/EcommEasy-Store.git
```

- **Run Application**

**P.S. Your backend (api) must be online. Follow this [README](https://github.com/EcommEasy/EcommEasy/blob/master/README.md) file before you run EcommEasy-Store.**

```shell
cd EcommEasy-Store
npm start
```
- **Install dependencies**
 ```shell
 npm i
 ```
 - **Start application in the background**
  ```shell
  pm2 start process.json
  ```

  - or you can start the app in your terminal:  
  
  ```shell
  npm start
  ```

Open http://localhost:3000 to see your store.  

