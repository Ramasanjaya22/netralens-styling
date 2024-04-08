# gluestack-ui-design-system

<h3 align="center">
  <br>
</h3>

## Introduction

**gluestack-ui-design-system** is a comprehensive design system built on top of the universal `gluestack-ui` library. It provides a collection of UI components , a Storybook for interactive development and testing, and a flexible configuration setup for seamless customization. It is a starter kit template to create your own Design System.

## Getting Started

- Click on `Use this template` button on the top-right corner.
- Clicking on `Create a new repository` will create a new repository with this template on your desired organization.
- Clone that repository from your codebase.
- Navigate to project directory
  ```bash
  cd gluestack-ui-design-system
  ```
- Install dependencies
  ```bash
    yarn
  ```

## Running Storybook

To interactively develop and test UI components, you can use Storybook. Follow these steps to run Storybook locally:

- Navigate to storybook directory

  ```bash
  cd example/storybook
  ```

- Run to storybook on the web
  ```bash
  yarn storybook
  ```
- Run to storybook on mobile
  ```bash
  yarn ios
  ```

## Customization

The gluestack-ui-design-system allows for easy customization to align with your project's requirements. To customize the design system, follow these steps:

- Customize design tokens (colors, sizes, media queries) and component themes in `packages/config` by adding, removing, or modifying entries.
- Adjust component functionality by adding, removing, or modifying features in `packages/themed`.

- To customize the branding with your own design system, navigate to the preview.js file within the .storybook folder and modify the relevant fields according to your branding preferences.

## Documentation

You can find detailed documentation of `gluestack-ui` for each component, including a list of props, examples, and customization at https://gluestack.io/ui/docs website.

## Tech Stack

JavaScript, React, React Native, Styled System

Licensed under the MIT License, Copyright © 2023 GeekyAnts. See [LICENSE](./LICENSE) for more information.
