
Read me


## Overview
A modern navigation system for SwiftUI applications featuring 
—stack-based navigation, 
—sheet presentation and 
—modular architecture for large-scale apps

## Features


## Architecture
ProjectRoot/
 ├── Networking/
 │   ├── APIConfig.swift        (Base URL)
 │   ├── GitHubEndpoint.swift   (Enum with paths)
 │   └── NetworkManager.swift   (The class you just created)
 ├── Models/
 │   └── Follower.swift         (The Decodable struct)
 ├── Services/
 │   ├── FollowersListService.swift         (The Protocol & Class)
 └── Scenes/
     └── FollowersList/
         ├── FollowersListView.swift
         └── FollowersListViewModel.swift   (Calls the Service)

## Contributors
Mohammad Nazim Uddin
Mob: 01712209861
Email: nazim.uddin.sean@gmail.com


