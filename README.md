# Welcome to your Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
   npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

### Other setup steps

- To set up ESLint for linting, run `npx expo lint`, or follow our guide on ["Using ESLint and Prettier"](https://docs.expo.dev/guides/using-eslint/)
- If you'd like to set up unit testing, follow our guide on ["Unit Testing with Jest"](https://docs.expo.dev/develop/unit-testing/)
- Learn more about the TypeScript setup in this template in our guide on ["Using TypeScript"](https://docs.expo.dev/guides/typescript/)

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.



**StickerSmash – React Native Mobile Application**

StickerSmash is a modern mobile application project developed with **React Native and Expo**, designed as a practical exploration of cross-platform mobile application development. The project demonstrates how a single JavaScript/TypeScript-based codebase can be structured to create applications capable of running across mobile platforms while taking advantage of the development workflow provided by Expo. The project is hosted on GitHub as **Sticker-Smash-react-native** and provides a foundation for developing an interactive sticker and image-oriented mobile experience.

The primary objective of StickerSmash is to build practical experience with the React Native ecosystem, Expo tooling, component-based application design, navigation, assets, and mobile user-interface development. Rather than treating mobile development as a collection of isolated screens, the project follows a structured application architecture in which application routes, reusable components, visual assets, configuration files, and TypeScript settings are maintained as separate parts of the project. This makes the application easier to understand, maintain, extend, and eventually transform into a more complete production-oriented mobile application.

The project is built on **Expo**, an open-source framework and development platform for React Native applications. Expo simplifies many aspects of mobile development by providing a development server, project tooling, device testing capabilities, and integration with the React Native ecosystem. The repository was created using the `create-expo-app` workflow, providing a clean starting point for building the StickerSmash application. The project can be installed with `npm install` and launched through `npx expo start`, allowing the application to be tested through development builds, Android emulators, iOS simulators, or Expo Go.

A major strength of the project is its **cross-platform development approach**. Instead of maintaining separate codebases for Android and iOS, React Native allows developers to construct user interfaces using reusable components and JavaScript/TypeScript logic. Expo further streamlines this process by providing tools that make it easier to develop and test applications across supported platforms. This approach reduces duplicated development work while encouraging reusable, component-driven application design.

The repository follows a structured directory organization. The **`app` directory** contains the application's routing and screen-related implementation, while the project uses **file-based routing** to organize application navigation. This architecture provides a clear relationship between application files and routes, making navigation easier to understand as the application grows. The **`components` directory** provides a dedicated location for reusable interface elements, supporting a modular development philosophy. The **`assets` directory** contains project resources used by the application, while configuration files such as `app.json`, `tsconfig.json`, and `package.json` define important aspects of the development environment.

TypeScript support is another important aspect of the project. TypeScript provides static typing on top of JavaScript, helping developers identify potential programming errors during development and making larger React Native applications easier to maintain. The presence of `tsconfig.json` establishes the project's TypeScript configuration and provides a foundation for developing more reliable and scalable application code.

The **component-based architecture** of React Native is particularly suitable for StickerSmash because user interfaces can be divided into smaller reusable building blocks. Instead of placing all interface logic into one large file, individual components can be developed, tested, styled, and reused independently. This approach improves code organization and provides a scalable foundation for adding additional sticker-management, image-editing, preview, sharing, and customization functionality in future versions.

The application also demonstrates the importance of **asset management in mobile development**. Images, icons, and other visual resources are maintained within the project's assets structure. Proper separation of application resources from application logic makes the codebase cleaner and allows visual elements to be updated without unnecessarily changing the application's core functionality.

From a development perspective, StickerSmash provides hands-on experience with several important technologies and concepts: **React Native, Expo, TypeScript, file-based routing, reusable components, mobile UI development, application configuration, package management, and cross-platform testing**. The project therefore serves not only as an application but also as a practical learning project for understanding how modern React Native applications are organized and developed.

The GitHub repository also demonstrates a standard software-development workflow. Source code, configuration files, documentation, and project resources are maintained under version control, making it possible to track development progress and manage future improvements. The repository includes a `.gitignore` file to help prevent unnecessary files from being committed, a package-lock file for dependency consistency, and an MIT license.

StickerSmash can be extended considerably beyond its current foundation. Future development could include a richer sticker-selection interface, image-picker integration, drag-and-drop sticker positioning, resizing and rotation, text overlays, image filters, photo sharing, saving edited images to device storage, custom sticker collections, improved animations, and enhanced user-interface design. Additional features could also include persistent local storage, user-created sticker packs, cloud synchronization, authentication, and social sharing capabilities.

The project is also a useful foundation for learning the complete lifecycle of a cross-platform mobile application. A developer can begin with the Expo starter structure, implement application screens and reusable components, introduce device capabilities, test the application on multiple platforms, optimize the interface, and eventually prepare production builds for distribution. This makes StickerSmash an adaptable project rather than a fixed demonstration.

Overall, **StickerSmash is a practical React Native and Expo project that demonstrates the fundamentals of modern cross-platform mobile application development**. Its structured `app`, `components`, and `assets` directories, TypeScript configuration, Expo tooling, file-based routing, and standard package-management setup provide a solid foundation for further development. The project combines learning, experimentation, and application architecture in a way that can be expanded into a feature-rich sticker and image-editing application. It represents hands-on experience with the React Native ecosystem and demonstrates how modern tools such as Expo and TypeScript can be combined to build maintainable, scalable, and cross-platform mobile applications from a unified codebase.


- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.
