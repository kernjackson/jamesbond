# To Build

## Install CocoaPods 

ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew install cocoapods

## Set up Workspace

git clone https://github.com/kernjackson/jamesbond.git
cd jamesbond
pod install
open JamesBond.xcworkspace 
