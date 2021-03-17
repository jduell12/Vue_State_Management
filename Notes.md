# What is Vuex?
- state management and pattern library
- used most commonly with the Vue framework
- very similar to Redux, Flux etc (but easier)
- centralized store for all components 

# Why use Vuex?
- components need to share state in many cases
- Vuex provides a single source of truth for data/state
- No need to pass events up and props down through multiple components
- Global state is "reactive"
    - update state in one component will update the same state in other components 

# Vuex Terms
- state
    - app-level state/data 
- getters
    - get pieces of state or computed values from state
- actions
    - called from components to commit a mutation
- mutations
    - mutate the state (update the data)
- modules
    - each module can have its own state, getters, actions and mutations


# Json Placeholder
- jsonplaceholder.typicode.com 
- able to placehold/prototype api calls 
- has various routes available to use to mock responses from an api

# Application - To dos with State Management
- Components
    - Todo
    - Add_toDo
    - filter_toDo
- state management
    - Vuex

# Vuex 
- boilerplate for module file 
```
const state = {};

const getters = {};

const actions = {};

const mutations = {};

export default {
  state,
  getters,
  actions,
  mutations,
};
```