# base16_python
Convert Base16 colors to Python dictionary containing RGB/Hex (TODO) values. For use primarily in Pillow

## How to use
Import the `colors` dictionary from the scheme file of your choice.

```py
from PIL import Image
from base16_{scheme} import colors
example = Image.new("RGB", 64x64, color=colors['base0A'])
example.show()
```