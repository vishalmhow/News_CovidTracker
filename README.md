
# NewsApp

This App will show news headline along with Covid Tracker.
In the Covid Tracker section we are showing Covid history data and can be filter by particular state.

App is wtritten in Xcode 13.2.1 & Swift 5, followed MVVM, used async/await for API calls & Concurrent operations and NSCache for Image Caching.

# Package Dependencies

# Charts library to rendar Covid data

I have implemented Charts library to represent Covid history data in the graphical manner

Before compiling the code need to download package dependency.

### CocoaPods

CocoaPods implementated for adding SwiftLint tool. SwiftLint is an open-source tool to enforce Swift style and conventions.

I have used CocoaPods & Package Dependencies both mechenism for adding third party library in this project. The purpose of using both mechenism to showcase way of using dependencies in the iOS App.

### Data Parsing / API Caller

I have implemented a generic function in the Service class which will work perpectly to call API with async / await mechenism. However, In this project I have commented out that function as I am not using that function because all the APIs are giving huge response and we don't need all data, we need only some data from that JSON response for this I have writtern customised function to fullfiled the needs.


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
