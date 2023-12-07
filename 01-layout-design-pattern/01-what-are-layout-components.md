# What are layout components?

> Layout components are components in React whose primary concern is helping us to arrange other components that we create on the page. Some examples of this that we are probably familiar with, and that we're going to be taking a look at throughout the rest of this chapter are split screens, arranging more than one component in different sections of the page. We also have lists and items, displaying data in a list, this is a surprisingly hard thing to get completely right. And modals, is just content that gets displayed over top of the actual page.

## How we normally create components

```jsx
<div styles={...}>
    <h1>Component Code ...</h1>
</div>
```

## How we leverage layout components

```jsx
<div styles={...}>
    {children}
</div>
```

- The main idea of layout components is that our components that we create, shouldn't know or care where it is that they're actually being displayed on the page.
- This can be taken care by outsourcing the layout styles into layout component, and then simply feeding the component to the layout component.

```jsx
<>
  <h1>Component Code ...</h1>
</>
```
