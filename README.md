# React Context API Project

This project was solely made by the intent to learn, understand and strengthen React Context API fundamentals.

## Leaarnings:
1. Creating React Context object for Global State Management. It simply means a creating a Global Object whose properties will be accessible to its children (nested) components.  -`context/UserContext.js`
2. Providing values/data of the Context to the children/nested components, by using `Provider` attribute of the created context. - `context/UserContextProvider.jsx`
3. Using `useContext()` hook to access and store/udpate the data in the created context, which we passed to the `values` prop of the `UserContext.Provider` component -`components/Login.jsx` & `components/Profile.jsx`
4. When we are using `UserContextProvider` as wrapper in `App.jsx`, then we are basically making the data stored in the `UserContext` accessible by the children/nested components, but they cannot read and use the data stored in the context, which is made possible by using `useContext()` hook.

Hence, this is the 1st Way or Approach of Using **React-Context-API** for **State-Management**.