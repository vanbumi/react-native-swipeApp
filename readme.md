# React Native SwipeApp with Expo

## Getting start

* Install Expo Desktop Client.
* Install Expo Device Client.
* Create New Project in Expo.
* Open code editor in project directory.

* Open file main.js
main.js is a root component for expo applications.

* Create new folder named src

* Create new file named src/Ball.js

      import React, { Component } from 'react';
      import { View } from 'react-native';

      class Ball extends Component {
        render() {
          return (
            <View style={styles.ball} />
          );
        }
      }

      const styles = {
        ball: {
          height: 60,
          width: 60,
          borderRadius: 30,
          borderWidth: 30,
          borderColor: 'black'
        }
      };

      export default Ball;

* On main.js import it:

      import Ball from './src/Ball';

and update the view:

    <View style={styles.container}>
      <Ball />
    </View>

* Save and device will refresh it self and the ball wil there in the right middle.    