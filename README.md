
# NewsApp

The App is a personalized news aggregator that organizes and highlights what’s happening in the world so that you can discover more about the stories that matter to you. This App will show news headlines along with Covid Tracker.

In the Covid Tracker section Allows you to filter the Covid history data by US States.


App is written in Xcode 13.2.1 & Swift 5, followed MVVM, used async/await for API calls & Concurrent operations and NSCache for Image Caching which helps with better performances.

# Package Dependencies

# Charts library to render Covid data

The history of Covid cases can be seen graphically in the App, the trend charts are user friendly. The Charts library is used to represent Covid history data in the graphical manner.

# Note: Before compiling the code need to download package dependencies.

### CocoaPods

The CocoaPods implemented for adding SwiftLint tool. SwiftLint is an open-source tool to enforce Swift style and conventions.

The CocoaPods & Package Dependencies mechanism are used for adding third party libraries in this project. The purpose of using both mechanism is to showcase way of dependencies in the iOS App.

### Data Parsing / API Caller

The Generic function is implemented in the Service class which will work seamlessly to call APIs with async / await mechanism. However, in this project this function is commented out it is not being used because all the APIs are giving huge responses and we do not need all data, we need only selected data from the JSON response, a customized function is written to address this requirement.


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

 My name is Vishal Sharma, I am based out of India. I have total 10 years of Experience working as Sr. iOS Developer. I have developed more than 30 applications single handedly, have rich experience working with customers of different industry verticals, let the projects from end to end, requirements gathering to solution design, development, testing and deployment. Received several appreciation from senior leadership of the customers for my work.

 I am passionate about learning new tech stacks and spend 5+ hours dedicatedly every week to improve my technical acumen.

 When I am not in front of my computer, I enjoy reading books, trekking and exploring new places.

 I am available on LinkedIn:

https://www.linkedin.com/in/vishal-sharma-a77ab030/ 
 

<img src="https://github.com/vishalmhow/NewsApp/blob/main/NewsApp.gif" width="414" height="896" />
