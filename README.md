# Atomic Blog

- Convert an app that relies heavily on prop-drilling into an application that uses Context API.

## Context API

The Context API contains three key elements.

1. **Provider** - Top-most, top-level componen (even higher than App in the component tree ) that contains the state and props that are stored and globally accessible to all components in the application that subscribe to the provider.
2. **Value** - Values are stored within the context.
3. **Consumers** - Components that subscribe to the provider context and can access the values that are stored in the context.

Creating a new context without any initialised variables. The name of the context must begin with a capital letter, because it is a separate component. `const PostContext = createContext();`
