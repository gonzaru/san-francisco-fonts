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

#### 2. Install the desired San Francisco Fonts:
For example, to install **SF Mono**:

    # (GNU/Linux, *BSD)
    $ mkdir -p ~/.local/share/fonts
    $ cp SF-Mono/* ~/.local/share/fonts/

    # (macOS, if they are not already pre-installed)
    $ mkdir -p ~/Library/Fonts
    $ cp SF-Mono/* ~/Library/Fonts/

#### 3. Rebuild the local user fonts cache (optional)
    # (GNU/Linux, *BSD)
    $ fc-cache -v -f

#### 4. Verify that the fonts are already installed
    # (GNU/Linux, *BSD)
    $ fc-list -f '%{family}\n' | grep '^SF ' | uniq

    # (macOS)
    $ system_profiler SPFontsDataType | grep -F 'Family: .SF ' | uniq