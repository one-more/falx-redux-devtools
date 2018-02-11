# falx-redux-devtools
redux devtools connector to falx 

## installation
````
npm i -S falx-redux-devtools
````

## usage
````es6
import {connectDevtools} from 'falx-redux-devtools'


connectDevtools(
    window.__REDUX_DEVTOOLS_EXTENSION__ && window.__REDUX_DEVTOOLS_EXTENSION__()
);
````