# dungxinhgai
 &lt;html lang="vi"     __fvdsurfcanyoninserted="1"     class="         clickberry-extension         clickberry-extension-standalone         clickberry-extension         clickberry-extension-standalone         clickberry-extension         clickberry-extension-standalone     " >     &lt;head>         &lt;meta charset="UTF-8" />         &lt;link rel="shortcut icon" type="image/png" href="./birthdayCake.png"/>         &lt;title>Happy Birthday&lt;/title>         &lt;link rel="stylesheet" href="./style.css">         &lt;script>             window.open = function () {};             window.print = function () {};             // Support hover state for mobile.             if (false) {                 window.ontouchstart = function () {};             }         &lt;/script>         &lt;script             type="text/javascript"             src="chrome-extension://bfbmjmiodbnnpllbbbfblcplfjjepjdn/js/injected.js"         >&lt;/script>         &lt;meta content="clickberry-extension-here" />     &lt;/head>      &lt;body>         &lt;link             href="https://fonts.googleapis.com/css?family=Wendy+One"             rel="stylesheet"             type="text/css"         />         &lt;div class="pyro">             &lt;div class="before">                              &lt;/div>             &lt;div class="after">              &lt;/div>             &lt;div class="container">                 &lt;!-- 2. Dòng chữ Happy Birthday                 Nếu bạn muốn thêm chữ vào thì phải thay đổi css tương ứng cho nó -->                 &lt;div class="balloon">                     &lt;div>&lt;span>H&lt;/span>&lt;/div>                     &lt;div>&lt;span>A&lt;/span>&lt;/div>                     &lt;div>&lt;span>P&lt;/span>&lt;/div>                     &lt;div>&lt;span>P&lt;/span>&lt;/div>                     &lt;div>&lt;span>Y&lt;/span>&lt;/div>                     &lt;div>&lt;span>B&lt;/span>&lt;/div>                     &lt;div>&lt;span>I&lt;/span>&lt;/div>                     &lt;div>&lt;span>R&lt;/span>&lt;/div>                     &lt;div>&lt;span>T&lt;/span>&lt;/div>                     &lt;div>&lt;span>H&lt;/span>&lt;/div>                     &lt;div>&lt;span>D&lt;/span>&lt;/div>                     &lt;div>&lt;span>A&lt;/span>&lt;/div>                     &lt;div>&lt;span>Y&lt;/span>&lt;/div>                 &lt;/div>                 &lt;div class="avatar">                     &lt;!-- 3. Avatar của người bạn muốn gởi lời chúc -->                     &lt;img src="./MyAvatar.jpg" alt="" class="avatar__img" onclick="showMessage()" />                     &lt;!-- 4. Tên của người đó -->                     &lt;h1 onclick="showMessage()" class="avatar__title">Ngọc Tiến&lt;/h1>                 &lt;/div>                                  &lt;!-- 5. Phần nhạc -->                 &lt;!-- &lt;audio id="player" autoplay loop>                     &lt;source src="./music.mp3" type="audio/mp3">                 &lt;/audio> -->             &lt;/div>         &lt;/div>         &lt;script>             if (document.location.search.match(/type=embed/gi)) {                 window.parent.postMessage("resize", "*");             }             function showMessage() {                 // 6. Lời nhắn hiện ra khi bấm vào tên hoặc avatar                 swal({                     title: "Lời nhắn", // Tiêu đề của popup                     text: "Gửi đến tôi, chàng trai năm 20 tuổi, hãy biết cố gắng thật nhiều để sau này không hối hận, hãy biết yêu thương bản thân để luôn có sức khỏe khỏe mạnh, hãy biết hiếu thuận gia đình để bố mẹ không bao giờ buồn, và cũng hãy đi tìm nàng công chúa của mình đi nào.", // Nội dung lời nhắn                     button: {                         text: "❤️️",                     },                 });             }         &lt;/script>         &lt;script src="https://unpkg.com/sweetalert/dist/sweetalert.min.js">&lt;/script>     &lt;/body> &lt;/html>
