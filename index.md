# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6
![Image of Hil Colish](https://cdn.myminifactory.com/assets/object-assets/5e650f8b89d95/images/720X720-ghost-flagship.jpg)
```python
import hashlib
import sys

try:
  test_str = sys.argv[1]
except KeyError:
  test_str = 'test_str'
finally:
  hash = hashlib.new('sha256', test_str.encode())
  print(f'Hash: {hash.hexstring()}')
```
- [x] Create basic class, e.g. `abc.ABC`
- [x] Create unit class
- [ ] Create specific unit class
- [ ] Create unittest file and class
- [x] Create combat class
- [ ] Prepare interface for combat
