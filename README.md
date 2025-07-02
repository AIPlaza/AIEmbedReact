<!-- markdownlint-disable MD030 -->

# Agentic Plaza Embed React

React library to display flowise chatbot on your website

![Flowise](https://github.com/FlowiseAI/FlowiseChatEmbed/blob/main/images/ChatEmbed.gif?raw=true)

## Install

```bash
npm install ai-plaza-embed@1.0.0 ai-embed-react
```

or

```bash
yarn add ai-plaza-embed@1.0.0 ai-embed-react
```

## Import

Full Page Chat

```tsx
import { FullPageChat } from "ai-embed-react";

const App = () => {
  return (
    <FullPageChat
      chatflowid="your-chatflow-id"
      apiHost="http://localhost:3000"
    />
  );
};
```

Popup Chat

```tsx
import { BubbleChat } from "flowise-embed-react";

const App = () => {
  return (
    <BubbleChat chatflowid="your-chatflow-id" apiHost="http://localhost:3000" />
  );
};
```
