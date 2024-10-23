# Mobility iQ - iOS Take-Home Test

## Objective
Using Swift and UIKit, build a simple app that fetches nearby restaurants and displays them as annotations on a MapKit map. Upon tapping an annotation, the user should be navigated to a detail view with some more information about the location.

## Setup
- Create a new iOS app using Swift and UIKit, the UI should be built programmatically, no Storyboards. Please delete `Main.storyboard`.
- The main screen should be a single view with a full-screen [MapKit](https://developer.apple.com/documentation/mapkit/) map view.
- Request access to the user’s current location using [CoreLocation](https://developer.apple.com/documentation/corelocation).

## Networking
- Use Google’s [Nearby Search](https://developers.google.com/maps/documentation/places/web-service/search-nearby) API to fetch restaurants near the user’s current location.

## User Interface
- Display the results from the Google API as MapKit annotations on the map view.
- Upon tapping an annotation, the user should be navigated to a detail view with some more information about the location. Consider using SwiftUI here.

## Bonus (Optional)
- Add a slider that lets the user change the radius of the [Nearby Search](https://developers.google.com/maps/documentation/places/web-service/nearby-search#nearby-place-search-examples).

## Evaluation Criteria
- Does the app work as expected? Is it performant?
- Is the code organised, readable and reusable?
- How is the project file hierarchy structured?
- What does the UI look like, i.e. does it fit in with iOS?
- Does the app have intuitive interactions?
- Are network requests made appropriately and efficiently?
- How does the app handle potential errors, i.e. no location access granted?
