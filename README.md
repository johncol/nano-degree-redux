# Redux Sample Project

This sample project is a poc of how to build a javascript application using a flex store to handle the state management.

First, a custom store was built, its API provided methods to get the state, dispatch actions, and subscribe to updates notifications. The application that used this store was a TODOs and goals management tool (create, delete, and toggle items). All the UI updates were done using the window.document API.

The app has been updated several times to:

- Use Redux instead of the custom store for state management
- Use React for handling UI operations
- Use ReactRedux to connect React components with the Redux store

Finally, we used the npm package called create-react-app to scaffold a new application, and the hole project structure was rearraged while maintaining the same behavior.

## Check it working at [github pages](https://johncol.github.io/nano-degree-redux/)
