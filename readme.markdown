# highlight

**highlight** provides easy interface for highlighting text using terminal
escape codes.

## Usage

```bash
echo "$(highlight fg red)red foreground$(highlight reset)," \
     "$(highlight bg white fg blue)white background with blue foreground$(highlight reset)" \
     "$(highlight bold) bold" \
     "$(highlight blink) bold blink"
```

## Installation

### Arch Linux

```
yaourt -S highlight-git
```
