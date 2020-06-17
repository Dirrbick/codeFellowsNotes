1. Why do we not need more .html pages in a multi-page React app?
  - the package **react-router-dom** has a __BrowserRouter__ component that is a container around what the current URL path would show.
2. If we wanted a component to show up on every page, where would we put it and why?
  - Inside a <Route />
    - The reason is that inside the route component it takes and renders other components that are nested inside of it.
3. What does props.children contain?
  - it contains anything that we put inside of the open and closing tags.