# react-library-example
https://habr.com/ru/post/461439/

> Simple example of react library with typescript, rollup, jest, storybook, eslint and prettier


## Usage

```tsx
import * as React from 'react';
import 'react-library-example/dist/index.css';
import { ExampleComponent } from 'react-library-example';

class Example extends React.Component {
   render() {
      return <ExampleComponent text="Test" />;
   }
}
```

## License

MIT ©
