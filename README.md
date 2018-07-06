# aussie-ipsum-react
React component to generate Aussie Ipsum, mate.

*WORK IN PROGRESS*

### Why?

You need filler code for tests, Storybooks, and other things. And... you like jokes.

### Props

```tsx
interface AussieIpsumProps {
  words?: number;
  paragraphs?: number;
  startWithLatin?: boolean;
  includeLatin?: boolean;
}
```

### Usage

```
yarn add aussie-ipsum-react
```

```tsx
import { AussieIpsum } from 'aussie-ipsum-react';

const ExampleComponent = () => (
  <AussieIpsum
    words="11"
    startWithLatin={true}
    includeLatin={false}
  />
);
```

Outputs: Lorem ipsum dolor sit amet bogan keen mate bloke tomato sauce.
