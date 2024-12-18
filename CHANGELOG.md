### 1.45.5

2024-12-18 05:40

### 1.45.4

2024-12-18 05:38

### 1.45.3

2024-12-18 05:04

### 1.44.8

2023-02-06 11:19

### 1.44.7

2023-02-06 11:14

#### IMPROVED

- Allow string arrays in template modifiers for Increment Templated

### 1.44.6

2023-02-06 11:01

#### IMPROVED

- Allow string arrays in template modifiers for Increment Templated

### 1.44.5

2023-02-06 10:21

#### IMPROVED

- Using extension READMEs to generate main README
- Updated READMEs
- Allow more complex mathematical equations with i and x in Increment Templated

### 1.44.4

2023-01-31 08:07

#### IMPROVED

- Using extension READMEs to generate main README
- Updated READMEs

### 1.44

* Fix SearchLink extension

### 1.43

* If SearchLink isn't installed, install it when running the SearchLink extension

### 1.42

* Fix nvUltra extension
* Add SearchLink extension

### 1.41

* Update WebMarkdown to allow for gather installs in /opt/homebrew/bin.

### 1.40

* Remove the popcliphtml2text CLI from WebMarkdown that was causing "malicious software" warnings. Now offers to download and install using the signed and notarized package.

### 1.38

* Fix a couple of bugs and improve output of html2text for WebMarkdown

### 1.35

* Convert WebMarkdown to use Swift-based HTML2Text, avoiding need for Python executable

### 1.34

* Fix for WebMarkdown, change to python3 and update html2text

### 1.33

* Fix for bad option default type in some of the plists.

### 1.31

* Increment Templated updates/fixes

### 1.28

* Add "Increment Templated" extension

### 1.27

* Add "HardWrap" extension

### 1.25

* Replace PreviewURL with CheckURLs
    * Allows results from preview navigation to modify selected text
    * Better icon

### 1.24

* Updated PreviewURL
    * Ignore URLs without http(s) protocol
    * Handle multiple URLs
    * Center preview pane on display

### 1.19 --- 1.23

* stupid commits because I'm having trouble with the build script. Don't mind me.

### 1.18

* Quick little format stripper (PoorText)

### 1.17

* Added "DefineAbbr" extension

### 1.16

* Updated (rewritten) blockquote extension

### 1.15

* Added "Sum" extension

### 1.14

* Added LinkCleaner and CopyCleanLinks extensions

### 1.12

* Added Twitterify extension.

### 1.11

* Added the WebMarkdown extension.

### 1.10

* Updated OpenURLS
    * Better regex for extracting URLs
    * Hold down Option to combine lines and fix broken urls
        * This can cause issues with full urls on consecutive lines, but is handy for a single broken link.
        * Leaves leading space on lines, so urls broken with an indent are still screwed. Ran into too many problems trying to parse around that.

* Added CopyURLs

    Duplicate of OpenURLs, but copies a plain, newline-separated list to the clipboard

* Added FixPoorlyObscuredEmails
    * Fixes "me AT here DOT com" style email obfuscations
    * Hold Option to compose new email for matched addresses

### 1.8

* Blockquote:
    * Handle line breaks better
    * Command-click to decrease quote level
    * Command-Option-click key to remove all quoting
    * don't quote reference link definitions
* BulletList: Bullet type configuration options, Command modifier to remove list formatting
* CopyPlus: Option modifier to concatenate strings with no extra whitespace
* Credits block for all extensions
* URLEncode extension (also available at [Pilot Moon](http://pilotmoon.com/popclip/extensions/page/URLEncode))

### 1.7

* Outdent: Command-click to outdent all lines fully
* Too Many Wrappers: Removed Shift-click options as they were breaking stuff.
* CopyPlus: Command-click to add extra linebreak between entries
