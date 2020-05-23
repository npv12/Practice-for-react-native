# Practice-for-react-native
a practice application based on EXPO with various functionality

On using Stack Navigator, the mehtod to use the same in react-native is diff. refer to the below code for that  
                                        import React from 'react';
                                        import HomeScreen from './Src/homeDir/home';
                                        import {NavigationContainer} from '@react-navigation/native'
                                        import {createStackNavigator} from '@react-navigation/stack'
                                        const Stack = createStackNavigator();
                                        function App(){
                                          return (
                                            <NavigationContainer>
                                              <Stack.Navigator initialRouteName="Home">
                                                <Stack.Screen name="Home" component={HomeScreen} /> 
                                              </Stack.Navigator>
                                            </NavigationContainer>
                                          );
                                        }
export default App;
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Home :  stackNavigator and uses. See documentation before using it.
        stackNavigator dependencies:  npm install react-native-gesture-handler react-native-reanimated react-native-screens 
                                        react-native-safe-area-context @react-native-community/masked-view
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------                                        
                                        
                                                    BASICS
ImageScreen :      reusing components and learning Props
Lists :            using flatlist
Counter:           using State
Random Color Gen : Random function + state functionality.. Also for inout text, use it like this only
squareScreen :     check state var and usasge of reducer
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
food App :         vector icons, using api (axios), hooks
NOTE: Never use react for expo. A lot of libs will be missing


