# webchat

A simple webchat widget to connect with a chatbot. Forked from [react-chat-widget](https://github.com/Wolox/react-chat-widget)
## Features

- Text Messages
- Quick Replies
- Images and Videos
- Snippet style for links (only as responses for now)
- Markdown support
- Easy to import in a script tag or as a React Component
- Persistent sessions

## Build tasks

There are 3 types of build tasks in the build process.

- `npm run build`: Build for development (instrumented code for code coverage)
   - Will bundle as `webchat-instrumented*.js`
- `npm run watch`: Build for development with watch mode loop
- `npm run prepublishOnly`: Build for production
   - Will bundle as `webchat*.js`

## Testing Web Chat for development purpose
