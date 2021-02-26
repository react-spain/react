# Crear app de react
```
npx create-react-app counter-app
npm start
```


# Template App Funcional Component.
```
import React from 'react';
import PropTypes from 'prop-types';

// Funcional Component
const CounterApp = ({ value }) => {

    if (! value){
        throw new Error( 'El value es neecsario' );
    }

    return (
        <>  
            <h1> CounterApp </h1>
            <h2>{ value }</h2>
        </>
        );
}

PrimeraAppp.protoTypes = {
    value: PropTypes.string.isRequired    
}

export default CounterApp;
```
