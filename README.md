# KittyJS

KittyJS is a super lightweight but complete AMD-compliant module loader with:

- Loader Plugin supported;
- Common Config supported, include BaseUrl、paths、packages、map、config and shim.

it was originally named as 'SimpleAndNaiveJS', since its implement is really simple. In fact, it just has about 600 source code lines, but it actually works. If you want to know how AMD loader works, you can try to read it, it's easier to understand.

## KittyJS vs requireJS
| Item      |  KittyJS | requireJS  | esl |
| :-- | --:| --: | --: |
| Size      | 2.8kb  |  6.2kb | 3.7kb |
| Performance  | - |  almost  | same |
| Shim support | YES | YES | NO |
| Timeout handler| NO | YES | YES |

## Test

fully tested by the [AMD Tests](https://github.com/amdjs/amdjs-tests) and [ESL Tests](https://github.com/zengjialuo/kittyjs/tree/master/test)

## Usage

```html
<script src="http://rigel.baidustatic.com/wg_biz/kitty/kitty.js"></script>
```

config options is same with requireJS, just try to replace the scirpt src.
