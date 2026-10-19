# WalkAnywhere

An iOS walking route tracker. Create custom walking routes, track your daily steps along them, and visualise your progress.

|         Main Route          |          Routes          |         Create Route          |      Step History       |
| :-------------------------: | :----------------------: | :---------------------------: | :---------------------: |
| ![](./images/mainroute.PNG) | ![](./images/routes.PNG) | ![](./images/createroute.PNG) | ![](./images/steps.PNG) |

## Features

### Route Planning
- **Interactive map** – tap to place start and end points
- **Automatic routing** – uses Apple Maps walking directions
- **Hybrid routing** – falls back to straight-line segments when no walking route is available
- **Route details drawer** – collapsible drawer showing distance and estimated steps

### Step Tracking
- **HealthKit integration** – tracks daily steps automatically
- **Progress visualisation** – progress bars showing route completion
- **Step history** – view the past 30 days of step data
- **Live updates** – progress updates in real time for the active route

### Route Management
- **Multiple routes** – create and store as many routes as you like
- **Main route** – star a route to make it your current journey
- **Edit and delete** – organise your saved routes
- **Persistent progress** – walking progress is saved automatically

## Built With
- **SwiftUI** – declarative UI
- **SwiftData** – persistent storage
- **MapKit** – maps and walking directions
- **HealthKit** – step counting

## Getting Started

### Requirements
- Xcode 26+
- iOS 26.2+ simulator or device (a physical device is needed to track real steps)

### Running the App
1. Open `walkanywhere.xcodeproj` in Xcode
2. Select a device or simulator
3. Press `Cmd + R` to build and run
4. Grant HealthKit permissions when prompted

## Usage

### Creating a Route
1. Go to **My Routes**
2. Tap the **+** button
3. Tap two points on the map
4. Review the calculated route
5. Tap **Save Route** and enter a name

### Setting a Main Route
1. Go to **My Routes**
2. Tap the star icon next to a route
3. View your progress in **Current Journey**

### Tracking Progress
- Daily steps count towards your main route automatically
- Progress is kept when you switch routes
- Completed routes are marked with a checkmark

## Development

- [CLAUDE.md](CLAUDE.md) – project configuration and architecture notes
- [PROMPTS.md](PROMPTS.md) – full development history of prompts

## License

All rights reserved.

## Credits

Designed and built by Zachary Upstone, 2026.
