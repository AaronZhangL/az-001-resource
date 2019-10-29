### 1. Find out dierctory
<pre>
環境準備
userChrome.cssの作成
Firefoxのプロファイルのパスへ移動する
FirefoxのURLバーに「about:profiles」を入力して、「プロファイルについて」ページを表示する
ルートディレクトリーのフォルダを開く
ルートディレクトリーのフォルダにchromeフォルダを作成する
chromeフォルダ内にuserChrome.cssファイルを作成する
下記の「userChrome.cssの動作確認」を参考に動作確認する
</pre>

### 2. Download css files and rename it to userChrome.css
https://github.com/MrOtherGuy/firefox-csshacks/blob/master/chrome/multi-row_tabs.css

### 3. Find out profiles root folder.
<pre>
Input [about:profiles] in firefox url area.
Open [root directory] directory.
Example: 
/Users/xxxxxxx/Library/Application Support/Firefox/Profiles/482exbzc.default-release
</pre>

### 4. Save userChrome.css files to chrome directory, if it is not exist mkdir it please.
<pre>
Example:
/Users/xxxxxxx/Library/Application Support/Firefox/Profiles/482exbzc.default-release/chrome
</pre>


#### Reference

https://www.bugbugnow.net/2018/04/firefox-userchromecss.html

https://superuser.com/questions/1351717/multi-row-tab-bar-in-firefox-quantum
