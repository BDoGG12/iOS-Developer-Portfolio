<a href="https://twitter.com/chriisong" target="_blank"><img src="https://img.shields.io/badge/twitter-@chriisong-blue.svg?style=for-the-badge&logo=twitter&logoColor=white"></a>

# Hub

[Hub](https://github.com/chriisong/GitHubFollowers) is a take-home project by [Sean Allen](https://github.com/sallen0400). Upon completion of the course, I have added some additional features such as Core Data and CloudKit capabilities, additional view controllers for smoother user experience, and changing the `FavouritesVC` to be UITableViewDiffableSource.

#### Technology: Diffable Data Source, Core Data, CloudKit, No 3rd-Party Libraries, Result Type, REST API

## Screen Recordings

### Core Data and CloudKit sync across devices of same iCloud account
![Alt Text](HubGifs/CloudKit.gif)

### Core Data and UITableViewDiffableDataSource
![Alt Text](HubGifs/Diffing.gif)

### SafariServices
![Alt Text](HubGifs/Safari.gif)

### Deleting UITableView Row with Snapshot and updating Core Data
![Alt Text](HubGifs/SnapshotDelete.gif)

### Deleting all UITableView Rows with Snapshot and updating Core Data
![Alt Text](HubGifs/CoreDataDeleteAll.gif)

# SongCare
**SongCare** is a personal project that I have started as a means to dig deeper into Swift and challenge myself to publish on the App Store. My father, who is a surgeon in Korea, and I architectured this app together, with our combined passion and plans for an improved health care system wherein patients can have direct and unimpeded access to their own health data, and wherein doctors, patients, and other healthcare professionals can have smoother and secure delivery of information and requests. This app is a small piece of a bigger scheme of this desire for improved health care system.

This app is still in beta testing phase. There are still a lot of features and functions to be added, bugs to be fixed, and refactoring to be done.

#### Technology: Core Data, CloudKit, UNNotification, Diffable Data Source, REST API
#### 3rd Party Libraries: FSCalendar, YPImagePicker, PanModal, Charts

## Screen Recordings

### Adding Reminders and Editing Reminders
![Alt Text](Gifs/Reminder.gif)

### Adding Lab Results using YPImagePicker
![Alt Text](Gifs/Lab-Results.gif)

### Add Prescription
![Alt Text](Gifs/Prescription.gif)

### REST API to download more drug data
![Alt Text](Gifs/DrugDB.gif)

### Updating Home view after making changes from other views
![Alt Text](Gifs/Blood-Glucose.gif)

# TarkovMarket
**TarkovMarket** started as a personal need for an app that can help me quickly view item prices to maximize my profits each raid in Battlestate Game’s *Escape From Tarkov*, a game that forever ruined my enjoyment of any other FPS games. It’s a simple app that retrieves item information from the game’s flea market, using a 3rd party API service. Users can select items to add to the favourite list so that they have quick access to item information at a glance. 

#### Technology: Core Data, CloudKit, Diffable Data Source, REST API, UIRefreshControl, ResultTypes
#### 3rd Party Libraries: None

## Screen Recordings

### UIRefreshControl to update prices 
![Alt Text](TarkovMarketGifs/UIRefreshControl.gif)

### Empty State View and updating Core Data Entity to toggle `isFavourited` property
![Alt Text](TarkovMarketGifs/EmptyState.gif)

### Using Diffable Data Source to filter search controller results
![Alt Text](TarkovMarketGifs/Diffing.gif)

### Sorting Core Data objects using NSPredicate
![Alt Text](TarkovMarketGifs/Sorting.gif)
