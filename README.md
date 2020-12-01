# NR React Hooks Snippets

![icon](./icon.png)

Code less, think more.

Folked from [react-hooks-snippets](https://github.com/alDuncanson/react-hooks-snippets)

## Supported Snippets

| Prefix | Snippet                                                    |
| ------ | ---------------------------------------------------------- |
| `clg`  | `console.log( xx )`                                        |
| `clgn` | `console.log("xx", xx)`                                    |
| `cls`  | `className={styles.$1}`                                    |
| `sty`  | `style={{ $1 }}`                                           |
| `esp`  | `e.stopPropagation(); e.preventDefault();`                 |
| `glb`  | `& :global($1){$2};`                                       |
| `v--`  | `var(--$1);`                                               |
| `elli` | `css text-overflow: ellipsis`                              |
| `ush`  | `const [xx,setXx] = useState(yy);`                         |
| `ueh`  | `useEffect` template                                       |
| `uch`  | `useCallback` template                                     |
| `umh`  | `useMemo` template                                         |
| `urh`  | `const $1 = useRef(${2:null})`                             |
| `uss`  | `const $1 = useSelector((state: iRootState) => state.$2);` |
| `usd`  | `const dispatch = useDispatch<Dispatch>();`                |
| `usc`  | `const { } = $1.useContainer();`                           |
| `imr`  | `import * as React from 'react';`                          |
| `imrh` | `import React, { xx } from 'react';`                       |
| `imd`  | `import { useSelector, useDispatch } from 'react-redux';`  |
| `ima`  | `import { xx } from 'antd';`                               |
| `imc`  | `import classnames from 'classnames';`                     |
| `ims`  | `import { ReactComponent as XxSvg } from 'xx.svg';`        |
| `iml`  | `import loadable from '@loadable/component';`              |
| `lmm`  | `const $1 = loadable(() => import('$1'));$0`               |
| `imc`  | `import classnames from 'classnames';`                     |
| `imt`  | a template of normal react component                       |
| `imdt` | a template of react component with Redux                   |
| `imut` | a template of unstaed-next                                 |

**imt**

```js
import React from 'react';
import styles from './index.module.less';
interface Props {

}
const FC = (props: Props) => {
  return (

  );
};
export default React.memo(FC);
```

**imtd**

```js
import React from 'react';
import styles from './index.module.less';
import { useDispatch, useSelector } from 'react-redux';
import { Dispatch, iRootState } from '../store';
interface Props {

}
const FC = (props: Props) => {
  const dispatch = useDispatch<Dispatch>();
  const  = useSelector((state: iRootState) => state.);
  return (

  );
};
export default React.memo(FC);
```

![icon](./example.gif)

## Add to your project

There are 2 ways you can add React Hooks Snippets to your project:

#### By command

Launch VS Code Quick Open (`Ctrl+P`), paste `ext install Orainsink.nr-react-hooks-snippets`, and press enter.

#### By the Extension Marketplace

Launch VS Code Extension Marketplace (Ctrl+Shift+X), search for `NR React Hooks Snippets`, and look for my logo!

## Contributing

Submit a pull request with your proposed fixes, changes, and/or improvements and I'll take a look!

## License

Usage is provided under the [MIT License](https://opensource.org/licenses/MIT). See LICENSE.txt for the full details.
