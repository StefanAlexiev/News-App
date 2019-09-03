# News App 📰

News app allows its user to be able to see latest breaking news and articles all around the world. In addition , every user has it own personal newspaper which will gives the possibility of browsing different categories based on the user interest.Furthermore , all articles could be saved in order to be read again later.



## DESIGN MOCKUPS

******Design made in SketchApp 54.1******

### Screenshots:  
*  ##### Login & Registration
<img src="https://i.ibb.co/MhhWqTS/Simulator-Screen-Shot-i-Phone-X-2019-08-07-at-23-28-20.png" alt="drawing" height="400" width="200"/>
<img src="https://i.ibb.co/K7RBrp7/Simulator-Screen-Shot-i-Phone-X-2019-08-07-at-23-28-46.png" alt="drawing" height="400" width="200"/>

*  ##### World News & Personal Newspaper
<img src="https://i.ibb.co/X4W70H7/Simulator-Screen-Shot-i-Phone-X-2019-08-07-at-23-26-50.png" height="400" width="200"/>
<img src="https://i.ibb.co/9Z4x5k4/Simulator-Screen-Shot-i-Phone-X-2019-08-07-at-23-27-36.png" alt="drawing" height="400" width="200"/>

<img src="https://i.ibb.co/QP8Mhgd/Simulator-Screen-Shot-i-Phone-X-2019-08-07-at-23-27-05.png" alt="drawing" height="400" width="200"/> 
<img src="https://i.ibb.co/gvty2Z1/Simulator-Screen-Shot-i-Phone-X-2019-08-07-at-23-27-15.png" alt="drawing" height="400" width="200"/>

* ##### Saved News & Profile
<img src="https://i.ibb.co/GkS02T8/Simulator-Screen-Shot-i-Phone-X-2019-08-07-at-23-27-21.png" alt="drawing" height="400" width="200"/>
<img src="https://i.ibb.co/jwfrbcs/Simulator-Screen-Shot-i-Phone-X-2019-08-07-at-23-28-01.png" alt="drawing" height="400" width="200"/>

*  ##### Bottom Navigation & Colours

![](https://i.ibb.co/RQCH9jB/bottom-navigation.jpg)

![](https://i.ibb.co/Rvd9D0P/Colours.png)



## Architecture & Design Patterns



### Architecture

##### - Model-View-Controller (MVVM)



The idea behind MVVM pattern is that each  ******View****** on the screen will be backed by a  ******View Model****** that represents the data for the view.



This means if we are building a News application then the view might consists of a UITableView which allows to display the news items and the view model will consists of the data representing the news item like title, description, publishedDate, author, source etc.



* ******Advantages******:



The key benefit is allowing true separation between the View and Model beyond achieving separation and the efficiency that you gain from having that. What that means in real terms is that when your model needs to change, it can be changed easily without the view needing to and vice-versa.

* ******Disadvantages******:

- Some people think that for simple UIs, MVVM can be overkill.
- Similarly in bigger cases, it can be hard to design the ViewModel.
- Debugging would be bit difficult when we have complex data bindings.

### Design Patterns
*  #### Singleton
The Singleton design ensures a **_*class only has one instance, and provides a global         point of access to it_***. The class keeps track of its sole instance and ensures that no other instance can be created. Singleton classes are appropriate for situations where it makes sense for a single object to provide access to a global resource. It usually uses lazy loading to create the single instance when it’s needed the first time.

*  #### Repository
Repository pattern is a software design pattern that provides an abstraction of data, so that your application can work with a simple abstraction that has an interface.

It also makes code more  **_*testable_*** as it allow us to inject as a dependency a mock                                     repository.
*  #### Coordinator
*  #### Presenter

## API

The used API gives access to news headlines, and search for articles from over 30,000 news sources and blogs.

"News API" is a simple and easy-to-use API that returns JSON metadata for headlines and articles live all over the web right now.
[More about the API](https://newsapi.org/)
### Endpoints
News API provides you some global parameters in order to simplify and organize your requests.
*  #### Top headlines
This endpoint provides live top and breaking headlines for a country, specific category in a country, single source, or multiple sources. You can also search with keywords. Articles are sorted by the earliest date published first.

This endpoint is great for retrieving headlines for display on news tickers or similar.

*  #### Everything
Search through millions of articles from over 30,000 large and small news sources and blogs. This includes breaking news as well as lesser articles.

This endpoint suits article discovery and analysis, but can be used to retrieve articles for display, too.

*  #### Sources

This endpoint returns the subset of news publishers that top headlines (/v2/top-headlines) are available from. It's mainly a convenience endpoint that you can use to keep track of the publishers available on the API, and you can pipe it straight through to your users.

## Examples  to follow

##### Use this format for convenience:

*  ###### MARK:

// MARK: Something

func name(_ something:) {}

*  ###### LifeCycle:

// MARK: - Lifecycle
override func viewDidLoad() {
super.viewDidLoad()
ActivityIndicatorManager.shared.createIndicator(imageView:  self.activityIndicatorImageView, view: self.view)

request()
setUp()
}



*  ###### Protocols:
func/protocol nameOfFunc/nameOfProtocol 
method()
} // no empty line after that

## Used Cocoa Pods

* 'SkyFloatingLabelTextField', '~> 3.0'
* 'Firebase/Core'
* 'Firebase/Auth'
* 'iOSDropDown'
* 'Alamofire', '~> 5.0.0-beta.5'
* 'Kingfisher'
* 'NVActivityIndicatorView'
* 'MXParallaxHeader'
* 'RealmSwift'
* 'SwiftLint'
* 'ReachabilitySwift'
* 'Popover'



## OTHER

- Programming Language - Swift 5

- Font - Raleway & Bebas Neue
-  [A way of commiting]([https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet))
