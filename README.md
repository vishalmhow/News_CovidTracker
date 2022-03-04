
# NewsApp

This App will show news headline along with Covid Tracker.
In the Covid Tracker section we are showing Covid history data and can be filter by particular state.

App is wtritten in Swift 5, followed MVVM, used async/await for API calls and Concurrent operations.

# Package Dependencies

# Charts library to rendar Covid data

I have implemented Charts library to represent Covid History Data in the graphical manner

Before compile the code just download package dependency.

### CocoaPods

CocoaPods implementated for adding SwiftLint tool. SwiftLint is an open-source tool to enforce Swift style and conventions.

I have used CocoaPods & Package Dependencies both mechenism for adding third party library in this project.

### Data Parsing / API Caller

I have implemented a generic function in the Service class which will work perpectly to call API with async / await mechenism. In this project I have commented out that function as I am not using the generic one because my all APIs are giving huge response and dont need all data to represent so that parsed only required JSON.


## API Reference

#### Get all items

```http
  GET https://newsapi.org/v2/everything?q=tesla&from=2022-01-27&sortBy=publishedAt&apiKey=
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get Covid History Data

```http
  GET https://api.covidtracking.com/v2/us/daily.json
```

#### To get State Specific Covid Data
```http
  GET https://api.covidtracking.com/v2/states/us/daily.json
```

#### Code Coverage of the News_App:


<img src="https://github.com/vishalmhow/News_App/blob/main/Code_Coverage.png" width="1500" height="467" />


## 🚀 About Me
I am iOS App developer!

# Hi, I'm Vishal! 👋

<img src="https://github.com/vishalmhow/NewsApp/blob/main/NewsApp.gif" width="414" height="896" />
