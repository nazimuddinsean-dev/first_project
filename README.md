
Read me


## Overview
A modern navigation system for SwiftUI applications featuring 
—stack-based navigation, 
—sheet presentation and 
—modular architecture for large-scale apps

## Features
Features: 

## Architecture
````
ProjectRoot/
 ├── Application/
 │   ├── AppDelegate.swift (For App Launch activity)
 │   ├── RootView.swift    (Entry View)
 │   └── SplashView.swift  (For splash animation)
 │   └── App.swift         (Main scene)
 ├── Networking/
 │   ├── APIConfig.swift        (Base URL)
 │   ├── Endpoints.swift        (Enum with paths)
 │   └── NetworkManager.swift   (Singleton class for fetching data from backend)
 ├── Extensions/
 │   └── Color+.swift         (Extension for color)
 │   └── View+.swift          (Extension for view)
 ├── Components/
 │   ├── BottomSheetView.swift     (View for presenting any sheet)
 │   ├── LoadingView.swift         (App loading view during API call)
 └── Features/
     └── Feature1/
         ├── Feature1NestedView1.swift
         └── Feature1NestedView2.swift   
     └── Feature2/
         ├── Feature2NestedView1.swift
         └── Feature2NestedView2.swift
````

## Contributors
**Mohammad Nazim Uddin** - 📱 Mobile: [01712209861](tel:01712209861) - 📧 Email: [nazim.uddin.sean@gmail.com](mailto:nazim.uddin.sean@gmail.com)


