---
title: "Exploring Frontend Technologies: React, Frameworks, and Data Fetching with TanStack Query and Axios"
datePublished: Sat Jun 29 2024 17:08:19 GMT+0000 (Coordinated Universal Time)
cuid: cly0dlu1j000d0al17ysgbcas
slug: exploring-frontend-technologies-react-frameworks-and-data-fetching-with-tanstack-query-and-axios
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1719679475142/24f11c82-7f90-429f-b1f6-1afb887555f7.webp
tags: reactjs, frontend-development, axios, data-fetching, tanstack-query

---

So, you find yourself thinking of frontend development. You have spotted an opportunity in the ever evolving tech space. You aspire to become a webmaster, a term used for developers decades ago. Where then do you start? What do you need to know before you venture into this diverse field?

For the next five or so minutes, we will talk about frontend development at a glance. We will also talk about a frontend technology you have probably heard a few too many times; ReactJS. Then we will compare data fetching technologies within React(ReactJS), specifically TanStack Query and Axios.

## Introduction to Frontend Technologies

Frontend technologies are the backbone of modern web development, responsible for creating the visual elements users interact with on a website or application. They encompass various tools, libraries, and frameworks that help developers build efficient and aesthetically pleasing user interfaces (UIs). Some of the common frontend technologies include:

* **HTML**: The standard markup language for creating web pages.
    
* **CSS**: Used to describe the presentation of a document written in HTML.
    
* **JavaScript**: A programming language that enables interactive web pages.
    
* **React**: A JavaScript library for building user interfaces.
    
* **Angular**: A platform and framework for building single-page client applications.
    
* **Vue.js**: A progressive framework for building UIs.
    

## Understanding React

React, developed by Facebook and released in 2013, is a popular JavaScript library designed to address the challenges of building dynamic, high-performing user interfaces. It introduces a virtual DOM to optimize updates and improve performance, and its component-based architecture promotes reusability and modularity, making code easier to manage. React's declarative approach allows developers to describe what the UI should look like, with React efficiently handling the rendering. These features, combined with a strong community and ecosystem, have led to its widespread adoption for building modern web applications.

## Data Fetching in React

Data fetching is a crucial aspect of web development, allowing applications to retrieve and display data from external sources such as APIs. Say for instance, you visit a webite that helps developers find remote jobs. You expect to click a Job Listings button that will display available jobs you can apply to. That is data fetching. In React, data fetching can be implemented in various ways, often using libraries like Axios or more specialized tools like TanStack Query.

### TanStack Query

TanStack Query, also known as React Query, is a powerful data-fetching library designed specifically for React applications. It simplifies data fetching, caching, synchronization, and updating of server state.

#### Key Features of TanStack Query

* **Caching**: Automatically caches query results and reuses them to minimize network requests.
    
* **Stale-While-Revalidate**: Ensures data is always fresh by fetching it in the background while displaying stale data.
    
* **Automatic Refetching**: Refetches data on events like window focus and network reconnection.
    
* **Pagination and Infinite Scrolling**: Supports complex data fetching patterns.
    
* **DevTools**: Provides tools for inspecting query states.
    

**Pros:**

* Declarative Hooks: Streamlines data fetching with hooks like useQuery and useMutation.
    
* Built-in Features: Offers caching, background data refetching, and synchronization.
    
* Developer Tools: Includes DevTools for query state inspection.
    

**Cons:**

* Framework Specific: Tailored primarily for React applications.
    

### Axios

Axios is a promise-based HTTP client for the browser and Node.js. It simplifies making HTTP requests to fetch or save data and offers features like interceptors, automatic JSON data transformation, and more.

#### Key Features of Axios

* **Promise-Based**: Uses Promises for handling asynchronous operations.
    
* **Interceptors**: Allows intercepting requests or responses before they are handled.
    
* **Automatic Data Transformation**: Automatically transforms JSON data.
    
* **Cancel Tokens**: Provides a way to cancel requests.
    
* **Client-Side Support**: Works in browsers and Node.js environments.
    

**Pros:**

* Promise-Based: Handles asynchronous operations effectively.
    
* Flexibility: Allows detailed control over request configurations and error handling.
    
* Middleware Support: Facilitates request and response transformations.
    

**Cons:**

* Manual Handling: Requires explicit state management for loading indicators and error handling.
    
* No Built-in Caching: Lacks automatic caching mechanisms.
    

## Comparing TanStack Query and Axios

While both TanStack Query and Axios can be used for data fetching in React applications, they serve different purposes and have unique strengths.

### Ease of Use

**TanStack Query**:

* **Declarative Approach**: Uses hooks like `useQuery` and `useMutation` to manage data fetching declaratively.
    
* **Built-In Features**: Offers built-in caching, background refetching, and query synchronization out of the box.
    
* **Less Boilerplate**: Reduces boilerplate code by handling common data-fetching patterns automatically.
    

**Axios**:

* **Imperative Approach**: Uses functions to make HTTP requests, which requires more manual handling of states and side effects.
    
* **Flexibility**: Provides more control over the request configuration and error handling.
    
* **Boilerplate Code**: Requires additional code for managing loading states, errors, and caching.
    

### Caching and Synchronization

**TanStack Query**:

* **Automatic Caching**: Automatically caches responses and manages cache invalidation.
    
* **Stale-While-Revalidate**: Ensures data freshness by refetching in the background.
    
* **Refetching Mechanisms**: Provides mechanisms for automatic refetching on events like window focus and network reconnection.
    

**Axios**:

* **No Built-In Caching**: Requires manual implementation or integration with other caching libraries.
    
* **Manual Synchronization**: Synchronizing data requires additional logic and state management.
    

### Developer Experience

**TanStack Query**:

* **DevTools**: Offers a set of DevTools for inspecting and managing query states.
    
* **Reduced Boilerplate**: Minimizes repetitive code, improving developer productivity.
    
* **Community and Ecosystem**: Active community and extensive documentation.
    

**Axios**:

* **Wide Adoption**: Popular and widely used, with a large community and numerous resources.
    
* **Middleware**: Supports middleware for request and response transformation.
    

### Performance

**TanStack Query**:

* **Optimized for React**: Designed specifically for React, optimizing rendering and reducing unnecessary re-renders.
    
* **Efficient Data Management**: Manages data efficiently with automatic caching and background refetching.
    

**Axios**:

* **General Purpose**: Suitable for any JavaScript environment, not specifically optimized for React.
    
* **Performance Control**: Offers more control over request configurations, which can be optimized for specific use cases.
    

## Conclusion

Choosing between TanStack Query and Axios depends on the specific needs of your project. If you need a powerful, declarative solution with built-in caching and synchronization tailored for React, TanStack Query is an excellent choice. On the other hand, if you require a flexible, promise-based HTTP client that works across different environments and provides more control over requests, Axios is a reliable option.

Now, I just joined the HNG internship to learn more about cool concepts in frontend development, like data fetching, and more.I look forward to deepening my proficiency in React and mastering the seamless integration of frontend and backend technologies. React Query's powerful features will undoubtedly enhance my ability to manage data-fetching efficiently.

To learn more about the HNG Internship and its opportunities, visit [HNG Internship](https://hng.tech/internship) and [HNG Hire](https://hng.tech/hire). By understanding and leveraging the strengths of React, I aim to build robust, efficient, and high-performance web applications, contributing effectively to the HNG community and beyond.

Here's to becoming a webmaster! See you on the other side!