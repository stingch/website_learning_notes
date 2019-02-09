# website_learning_notes
# HTML5簡介
HTML是一種標記語言，一個HTML網頁是以多個tag(標籤)組成。運用不同的標籤能使瀏覽器在畫面上呈現網頁的布局和內容。
基本的HTML架構:
<!DOCTYPE HTML>
<html>
  <head>
    <metacharset="UTF-8">
    <title> Example </title>
  </head>
  <body>
    網頁內容
  </body>
</html>

由<>框的文字就是標籤

<!DOCTYPE HTML>標籤用來向瀏覽器宣告網頁的HTML版本，宣告 Document Type Definition, DTD(文件類型定義)。此為HTML5的宣告方式

<html> </html>標籤是HTML檔案開始和結束的標記，所有和網頁有關的元素會存放在這兩個標記之間，只要任何一個純文字檔中加入這個標記，並以副檔名html儲存，就會被視為網頁由瀏覽器開啟。

<head>標籤
  HTML的檔案資訊會存放在<head> </head>之間，常用的資訊包括網頁資訊(meta)、標題(title)、CSS和javascript等
  網頁資訊(meta):包含編碼(charset)、描述(description)、關鍵字(keywords)、作(author)、版權(copyright)等，通常在開發時會選擇UTF-8編碼
  標題(title): 網頁最頂部的標籤，會被搜尋引擎作為搜尋關鍵字參考，以上面的程式為例，網頁顯示的標題是Example
  CSS和javascript: CSS和javascript也被寫在head標籤中

<body>標籤
  <body>標籤存放網頁內文開始與結束的標記，網頁輸出的元素會被放在body裡，像是圖片、影片、音樂、表單、表格等
