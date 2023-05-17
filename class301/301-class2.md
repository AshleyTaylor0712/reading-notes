# Class 02 Reading Notes

## React Lifecycle Events

- Three phases:
  - Mounting
  - Updating
  - Unmouting

### Mounting

- Component Created & placed in DOM

### Updating

- Component is rerendered due to change/update

### Unmounting

- Component is removed from the DOM

## Props (Properties)

- Enables data handover from parent component to child component

- Types of data that can be passed include:
  - strings, numbers, booleans, objects, arrays, functions, react elements

- Props are read only in the child component. Unable to modify values

- Can be passed as a single object or individual arguments

## State  

- built-in object within React components
- represents the internal component state
- Used to manage data changes and can be modified by using the setState method

## Re-Render

- Occurs when a components props or states change
