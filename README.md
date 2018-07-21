# Puzzle15-iOS

## Overview

A native iOS [15-tile puzzle game](https://en.wikipedia.org/wiki/15_puzzle) using data and images made publicly available through the [Unsplash API](https://unsplash.com/developers). Features of the app:

* Get an image from Unsplash and break it into 15 tiles
* Randomize the tiles without rendering the puzzle unsolvable
* Move the tiles
* Play the next set of tiles when the puzzle is completed

## Run the App

1. Install Cocoapods

   ```bash
   $ bundle
   ```

1. Install Swift dependencies needed by the project

   ```bash
   $ pod install
   ```

1. Open the project in Xcode and run

   ```bash
   $ open Puzzle15.xcworkspace
   ```