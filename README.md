# San Francisco Fonts

### **Original files from:**
- [SF Pro](https://devimages-cdn.apple.com/design/resources/download/SF-Pro.dmg)
  - [https://devimages-cdn.apple.com/design/resources/download/SF-Pro.dmg](https://devimages-cdn.apple.com/design/resources/download/SF-Pro.dmg)
- [SF Mono](https://devimages-cdn.apple.com/design/resources/download/SF-Mono.dmg)
  - [https://devimages-cdn.apple.com/design/resources/download/SF-Mono.dmg](https://devimages-cdn.apple.com/design/resources/download/SF-Mono.dmg)
- [SF Compact](https://devimages-cdn.apple.com/design/resources/download/SF-Compact.dmg)
  - [https://devimages-cdn.apple.com/design/resources/download/SF-Compact.dmg](https://devimages-cdn.apple.com/design/resources/download/SF-Compact.dmg)
- [SF Arabic](https://devimages-cdn.apple.com/design/resources/download/SF-Arabic.dmg)
  - [https://devimages-cdn.apple.com/design/resources/download/SF-Arabic.dmg](https://devimages-cdn.apple.com/design/resources/download/SF-Arabic.dmg)

### Installation:

#### 1. Clone the repository:
    $ git clone https://github.com/gonzaru/san-francisco-fonts.git
    $ cd san-francisco-fonts

#### 2. Install the desired San Francisco font:
For example, to install **SF Mono**:

    $ mkdir -p ~/.local/share/fonts
    $ cp SF-Mono/* ~/.local/share/fonts/

#### 3. Rebuild the local user fonts cache (optional)
    $ fc-cache -v -f

#### 4. Verify that the font is already installed
    $ fc-list -f '%{family}\n' | grep '^SF ' | uniq