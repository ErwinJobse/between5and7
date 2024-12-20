# isbetween5and7



A simple package to check if a number is bewteen 5 and 7



## Installation



```bash

npm install iszero-or-less

```



## Usage



```typescript

import between5and7 from 'between5and7';



between5and7(6); // true


between5and7(1); // false

```


## API



### `between5and7(num: number): boolean`



Returns `true` if the input number is between 5 and 7 or  `false` if not


### Running Tests



```bash

npm test

```



### Building



```bash

npm run build

```


## Publishing



1. Update version in `package.json`

2. Build the package: `npm run build`

3. Run tests: `npm test`

4. Publish to npm: `npm publish`



## License

MIT

