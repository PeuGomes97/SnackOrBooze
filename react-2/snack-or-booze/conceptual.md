### Conceptual Exercise

Answer the following questions below:

- What is the purpose of the React Router?

React Router is used for managing navigation and rendering components in React applications, enabling dynamic routing by mapping specific URLs to components.

- What is a single page application?

Is a web application that operates within a single HTML page, dynamically updating the content as the user interacts with it, typically without needing to reload the entire page from the server.

- What are some differences between client side and server side routing?

Client-side routing: Routing logic is handled by the browser, allowing for faster navigation between pages without server round-trips.
Server-side routing: Each navigation request triggers a server request for a new page, resulting in longer loading times but ensuring SEO compatibility and better initial page load performance.

- What are two ways of handling redirects with React Router? When would you use each?

With useNavigate Hook - Useful for "You're now done here, go here instead, if you go back, no worries!

With the Navigate Componente - Useful for "You shouldn't have gotten here, go here instead, do not go back!

- What are two different ways to handle page-not-found user experiences using React Router? 

Render a <Route> with a wildcard path (<Route path="*" />): Matches any path not matched by previous routes, allowing for a custom 404 page

Or you'll redirect them to the root route "/"

- How do you grab URL parameters from within a component using React Router?

Use the useParams() hook: Provided by React Router, it allows extracting URL parameters directly within a functional component.

- What is context in React? When would you use it?

Context provides a way to pass data through the component tree without having to pass props manually at every level. It's useful for sharing data that is considered global or application-wide among components.

- Describe some differences between class-based components and function
  components in React.

  Class-based components: Use ES6 classes for component declaration, manage state using this.state and lifecycle methods.
  Function components: Use JavaScript functions for component declaration, can utilize hooks like useState() and useEffect() to manage state and lifecycle effects.

- What are some of the problems that hooks were designed to solve?

  Reuse stateful logic between components without using class-based components or higher-order components.
  Simplify complex component structures and reduce code duplication.
  Encourage better code organization by separating concerns like state management and side effects from component rendering.