
# NR React Hooks Snippets

![icon](D:\work_space\nr-react-hooks-snippets\icon.png)

Code less, think more.

Folked from [react-hooks-snippets](https://github.com/alDuncanson/react-hooks-snippets)


## Supported Snippets

| Prefix  | Snippet |
| ------------- | ------------- |
| `clg` | `console.log( xx )` |
| `clgn` | `console.log("xx", xx)` |
| `ush` | `const [xx,setXx] = useState(yy);` |
| `ueh` | `useEffect` template |
| `uch` | `useCallback` template |
| `umh` | `useMemo` template |
| `urh` | `const $1 = useRef(${2:null})` |
| `uss` | `const $1 = useSelector((state: iRootState) => state.$2);` |
| `usd` | `const dispatch = useDispatch<Dispatch>();` |
| `imr` | `import * as React from 'react';` |
| `imrh` | `import React, { xx } from 'react';` |
| `imd` | `import { useSelector, useDispatch } from 'react-redux';` |
| `ima` | `import { xx } from 'antd';` |
| `imc` | `import classnames from 'classnames';` |
| `ims` | `import { ReactComponent as XxSvg } from 'xx.svg';` |
| `imt` | a template of normal react component |
| `imtd` | a template of react component with Redux |

**imt**

```js
import React from 'react';
import styles from './index.module.less';
interface IFC {

}
const FC: React.FC<IFC> = (props) => {
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
interface IFC {

}
const FC: React.FC<IFC> = (props) => {
  const dispatch = useDispatch<Dispatch>();
  const  = useSelector((state: iRootState) => state.);
  return (

  );
};
export default React.memo(FC);
```

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
