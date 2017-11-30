# __Syng | 词应__
##### Dictionary App | 词典应用
##### v1.0.0
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)

---

## __About__
Syng is a free, open source, Chinese-To-English and English-To-Chinese Dictionary app that makes it easy to lookup words and phrases quickly. Currently Syng works on macOS, Windows, and Linux systems. 

### Name
Syng is a stylized spelling of cíyīng, the Pinyin for 词应. 词应 has been shorted from 词典应用, literally translating to Dictionary App.

## __Features__
- ___Search___
    - Syng allows you to search by Pinyin, English, and Chinese characters (both traditional and simplified)
- ___Study___
    - Syng makes it easy to study Chinese by creating flash cards out of your saved words and searches.
    - Syng also tests you on your knowledge and progress of your Chinese to measure your language development.
- ___Bookmarks___
    - Syng allows you to save words and searches to your bookmarks, so that you can reference them later, and even create custom vocab lists.
- __Offline Support__
    - No internet connection required! 
- __Cross-Platform__
    - Mac OS X
    - Windows
    - Linux
- __Prettify Pinyin__
    - Convert pinyin with tone numbers with tone marks
- __Convert Characters__
    - Convert between traditional and simplified characters
- __Pinyinify__
    - Convert 汉字 into hànzì. Turn characters into pinyin

## __What's new?__
Syng v1.0.0 is the biggest release yet, with some welcome new changes. For a full list of changes, see [the changelog](https://github.com/sotch-pr35mac/syng/blob/master/CHANGELOG.md).
1. Brand new user interface
2. 70% faster load time
3. Custom vocabulary lists
4. Notes
5. New Icon
6. Pinyinify characters
7. General stability and performance updates

## __Installing__
#### __Linux__
To install Syng on Linux, you can you use the pre-built installation script by copy and pasting the code below into terminal. __It's good to be cautious about what you are putting in your terminal, you can read the 64-bit install script [here](https://gist.github.com/sotch-pr35mac/3120195991d8879ef82569720371f18d) and the 32-bit install script [here](http://www.syngdict.com/).__

For 64-bit systems:
```
wget -O- https://goo.gl/1WdZyN | bash 
```
For 32-bit systems: 
```
wget -O- https://goo.gl/h42ejc | bash 
```

Alternatively, if you aren't comfortable running the pre-built installation script, you can install manually by downloading the 64-bit candidate [here](https://github.com/sotch-pr35mac/syng/releases/download/v1.0.0/Syng-linux-x64.tar.gz) and the 32-bit candidate [here](https://github.com/sotch-pr35mac/syng/releases/download/v1.0.0/Syng-linux-ia32.tar.gz) and then following the installation instructions provided.
#### __macOS__
To install Syng on macOS, simply download the `.dmg` file from [here](https://github.com/sotch-pr35mac/syng/releases/download/v1.0.0/Syng-macOS.dmg) and then drag and drop the Syng app into your Applications folder.
#### __Windows__
To install Syng on Windows, you can download the 64-bit installer from [here](https://github.com/sotch-pr35mac/syng/releases/download/v1.0.0/Syng-Windows-setup-x64.exe) and the 32-bit installer from [here](https://github.com/sotch-pr35mac/syng/releases/download/v1.0.0/Syng-Windows-setup-ia32.exe) and use it to install Syng.

## __Built On__
   - [Electron](http://electron.atom.io)
      - Framework for Native Cross-Platform Support
   - [CC-CEDICT](http://www.mdbg.net/chindict/chindict.php?page=cedict)
      - Chinese Dictionary Database
      - The file has been modified to JSON using the [Syng Dictionary Creator](https://github.com/sotch-pr35mac/syng-dictionary-creator)
   - [Vue.js](https://vuejs.org/)
      - Framework for building user interface
   - [IView UI](https://www.iviewui.com/)
      - User Interface Framework
   - Heavily modified version of [node-cc-cedict](https://github.com/johnheroy/node-cc-cedict) by [John Heroy](http://johnheroy.com/)
      - Node.js framework for CC-CEDICT Dictionary
      - Modified to work using hashmaps and support English, and pinyin search functionality.
   - [Franc](https://github.com/wooorm/franc)
      - Language Detection for Search

## __Developers Welcome__
If you're interested in contributing to Syng, you can checkout [the Roadmap](https://github.com/sotch-pr35mac/syng/blob/master/ROADMAP.md), or feel free to [contact me](mailto://p.wanstobas@gmail.com) and we can build great software together. 

## __Contribute__
This is a [Commitizen Friendly](https://github.com/commitizen/cz-cli) Repository. When contributing please use commitizen when committing changes.
You can install commitizen using npm:
```
npm install -g commitizen
```
1. Fork it!
2. Create a branch `git checkout -b my-feature`
3. Commit your changes `git cz`
4. Submit a pull request

## __Getting Started__
1. First go to the project directory
    `cd /path/to/project/`
2. Install the dependencies
    `npm install`
3. Run Syng
    `npm start`

## __Contributors__
- [Preston Wang-Stosur-Bassett](http://www.stosur.info)

## __License__
This software is licensed under the [GNU Public License 3](https://www.gnu.org/licenses/gpl-3.0.en.html).
