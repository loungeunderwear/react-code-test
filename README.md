<div align="center">
<a href="https://loungeunderwear.com"><img width="1200" src="https://cdn.shopify.com/s/files/1/0929/1494/files/lounge-header.jpg?v=1657202657"/></a>
</div>

# Lounge - React code test

> Lounge's React Design System - Create a component.

## Directory Structure
```sh
react-code-test/
├── .storybook                  # Storybook config
├── .vscode                     # Editor config
├── src                         # Base - (write your code here)
├── dist                        # Roll up output
└── ...                         # ...
```

## Task

### Get Started
#### Install dependencies and build workspaces

```sh
yarn && yarn start
```

### Create a button component

From the following Figma design, create a button component using Storybook, React, Styled Components & Jest
https://www.figma.com/file/6IsaMLS5RdQhI8DnC9H94J/Tech-Test-System

- The button styles should be defined using [Styled-components](https://styled-components.com/)
- The button should have three variants: Primary, Secondary and Tertiary. Use the [Styled-system](https://styled-system.com) - https://styled-system.com/variants/ to create these variants.
- The button should have a loading state.
- The button should have the ability to add an icon.
- The button should have the ability to be disabled.

### Set up Jest

**Create two tests for the Button component.**

- One test should be to test the button in a disabled state, to ensure it doesn't run any action.
- Come up with a second test for the button, which you feel would be helpful.

### Showcase your button in Storybook

- Create a `index.stories.tsx` file
- Showcase several use cases for your button component
