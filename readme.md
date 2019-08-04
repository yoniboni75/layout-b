# Layout B 
job interview assignment by Yonatan Lev Ari  
[demo]( https://3dyonic.github.io/layout-b)

## Specification
1. Container min-width: 300px
1. No media query
1. Visual referance is in the referance folder

## Development dependencies:
simple npm configuration with node sass


### Highlights
A simple html component with scss setup.  
This exercise demonstrate a flex based responsive layout without media queries. 

#### Expected beheviour: 
1. responsive grid
1. min container width: 300px
1. no media query

## Styling methods: 
- scss with sass-lint configuration
- role based architecture
  - seperation between global and component scope.
  - configuration based for global and component scope.
  - style guide as a global definition layer
- BEM ,OOCSS.
- Component selectors are self containted and isolated.  
  - using global tokens for configuration
  - using global mixins and functions
- Utilized mixins and functions for selector indipendent future re-use.
- Rule based linting


### Styling dependencies: 
- Since i wanted to simulate a real use case i chose the seperate between the component to external layers.
- external layers for this example are:
  - global config (containing the style guide and semantic tokens, very minimalistic for this component example)
  - base layer (reset)

### Notes:
For this example css folder contains the final output in styles.css but also contains:  
- global.css  
- layout-b.css  
i did it so we can also bench mark standalone output. 
therfore these files are not prefixed with '_" (against the common practise).

#### Performance statistics:
External requests: 0  
Global Size: 90 bytes  
Component Size: 250 bytes  
Total: 341 bytes    
Lint Errors: 0
