# Missing Return Statement in Next.js 15 Page Component

This repository demonstrates a common error in Next.js 15: forgetting to include a return statement in a page component.  Failure to do so will result in a runtime error. The solution shows how to correct this.

## Bug

The `pages/about.js` file is missing a `return` statement in its functional component. Next.js 15 requires all page components to return JSX. 

## Solution

The solution simply adds a `return` statement to the `About` component, returning a simple JSX element.