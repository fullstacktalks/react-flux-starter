# Flux Lab

Full Stack, March 12, 2015

## Getting started

- Clone this repo and go to it:
 
  ```
  cd ~/code # or wherever you keep code
  git clone git@github.com:fullstacktalks/react-flux-starter.git
  cd react-flux-starter
  ```
  
- Start a web server:
 
  ```
  python -m SimpleHTTPServer 8000
  ```
  
- Open the project in a browser (`http://localhost:8000/lab/`):

  ![image](https://cloud.githubusercontent.com/assets/2231765/6630596/f9452cb8-c8d7-11e4-9c92-0e9751e2d350.png)

- Open the project in your code editor.

## Tasks

1) __Display the currently selected city.__ You'll need to:
  - Create a new React component called `Display`
  - Render that component into `#display`
  - Make the component read its state from `SelectedValueStore`
  - Make the component listen for changes from `SelectedValueStore`

2) __Display the number of times a selection has been made.__ You'll need to:
  - Add a new store for this value, `SelectionCountStore`
  - Make the store listen for `VALUE_WAS_SELECTED` in the dispatcher
  - Use those events to update the store's value and update subscribers
  - Display that value in your new component
