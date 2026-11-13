# Agent Mode Guidance (Non-Obvious Only)

* **No Build Process**: There are no package files (`package.json`, `package-lock.json`, etc.). Do not run `npm`, `yarn`, or `pnpm` commands in this project.
* **Testing & Preview**: Test changes locally by executing `open index.html` on macOS. This starts the native default web browser with zero server prerequisites.
* **Mascot Asset Location**: The mascot image is stored at `./Bob_image.png` at the root. If you are modifying or replacing this image, do not change its dimensions or location, and ensure the `.bob-avatar` CSS container preserves its `overflow: hidden` attribute to keep it circular.
* **Style Structure**: Maintain strict 2-space indentation, kebab-case for HTML elements/CSS classes, and camelCase for JavaScript functions/variables.
