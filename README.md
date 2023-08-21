[![MELPA](https://melpa.org/packages/isortify-badge.svg)](https://melpa.org/#/isortify)

# isortify
> (automatically) format python buffers using isort

[![CI](https://github.com/pythonic-emacs/isortify/actions/workflows/test.yml/badge.svg)](https://github.com/pythonic-emacs/isortify/actions/workflows/test.yml)

## 💾 Quickstart

To automatically format all Python buffers before saving, add the function
`isortify-mode` to `python-mode-hook`:

```elisp
(add-hook 'python-mode-hook 'isortify-mode)
```
