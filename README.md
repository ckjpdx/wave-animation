# wave-animation
a simple, non-interactive scene using scss and repeating keyframe animations

## Purpose
This project was for practicing 

## Synopsis
This very simple project was an exercise in CSS keyframe animations. It has no functionality and currently only works for horizontally oriented screens. 

## Tech Used
SCSS was used for its ability to create rules via looping. 
```
@for $i from 1 through $wave-count {
  @if $i % 2 == 0 {
    $isReversed: -1;
  } @else {
    $isReversed: 1;
  }
  @if $isReversed == -1 {
    $skew1: -20deg;
    $skew2: 20deg;
  } @else {
    $skew1: 20deg;
    $skew2: -20deg;
  }
```
## Usage
Clone from github or view the site deployed: gh-pages 

## Tests

## Contributors

## License
