# SwiftUI MVVM Folder Architecture

A clean, organized, and maintainable SwiftUI project structure implementing the MVVM (Model-View-ViewModel) architecture pattern.

## Project Structure

```
SwiftUIMVVMFolderArchitecture/
│
├── Application/
│   └── SwiftUIMVVMFolderArchitectureApp.swift
│
├── Extensions/
│   └── Colors.swift
│
├── Models/
│   └── UserModel.swift
│
├── Resources/
│   └── Assets.xcassets
│
├── Services/
│   └── NetworkService.swift
│
├── Utils/
│   └── Constant.swift
│
├── ViewModels/
│   └── LoginViewModel.swift
│
└── Views/
    ├── Pages/
    │   ├── HomePageView.swift
    │   └── LoginPageView.swift
    │
    └── WidgetComponents/
        └── CustomButtonWidget.swift
```

## Architecture Overview

This project follows the MVVM (Model-View-ViewModel) architecture pattern to ensure separation of concerns and maintainability:

### 🏗️ Core Components

- **Models**: Data structures that represent the application's domain entities
- **Views**: SwiftUI views responsible for displaying the UI and forwarding user actions
- **ViewModels**: Classes that handle business logic and transform model data for views

### 📁 Folder Organization

- **Application**: Contains the main app entry point
- **Extensions**: Holds Swift extensions for added functionality
- **Models**: Contains all data models used in the application
- **Resources**: Stores assets, fonts, and other resources
- **Services**: Houses network, data persistence, and other service layers
- **Utils**: Contains utility classes and constants
- **ViewModels**: Stores all view models organized by feature
- **Views**: Contains all SwiftUI views organized by:
  - **Pages**: Main screen views
  - **WidgetComponents**: Reusable UI components

## Key Benefits

- **🧩 Separation of Concerns**: Clear boundaries between data, logic, and presentation
- **📱 Testability**: Easy to unit test view models and services
- **♻️ Reusability**: Components organized for maximum reuse
- **🚀 Scalability**: Easy to add new features without disrupting existing code
- **🔍 Maintainability**: Code is organized logically making it easier to find and modify

## Getting Started

1. Clone the repository
2. Open `SwiftUIMVVMFolderArchitecture.xcodeproj` in Xcode
3. Build and run the project

## Testing

The project includes:
- Unit tests for testing models, view models, and services
- UI tests for testing the user interface

## License

[MIT License](LICENSE)
