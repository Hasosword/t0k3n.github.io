# t0k3nlmao
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8"/>
    <meta
      name="viewport"
      content="width=device-width, initial-scale=1.0, shrink-to-fit=no"/>
    <title>ProXz</title>

    <link rel="shortcut icon" content="favicon.ico" />
    <link rel="stylesheet" href="index.css" />
    <script src="uv/uv.bundle.js" defer></script>
    <script src="uv/uv.config.js" defer></script>
    <script src="register-sw.js" defer></script>
    <script src="search.js" defer></script>
    <script src="index.js" defer></script>
    <script src="opt.js" defer></script>
    
  </head>

  <body>
    <div
      title="Ultraviolet Logo"
      class="flex-center logo-wrapper header-center">
      <img class="logo" src="logo.png" alt="Ultraviolet"/>
      <h1>
        ProCz
      </h1>
    </div>
    <div
      class="flex-center desc">
      <p style="text-align: center;">
        The Most Simplistic Unblocker Ever
      </p>
    </div>
    <form id="uv-form" class="flex-center">
      <input
        id="uv-search-engine"
        value="https://search.brave.com/search?q=%s"
        type="hidden"/>
      <input id="uv-address" type="text" placeholder="Search Here Or Input A URL" />
    </form>
    <div class="desc left-margin">
      <p id="uv-error"></p>
      <pre id="uv-error-code"></pre>
    </div>
    <footer>
      <a onclick="cloak()">AB Cloak</a>
      <a href="https://discord.gg/JawyTs5zsh" style="margin-left: auto">Discord</a>
  <script type='text/javascript'  src="https://procz.herokuapp.com/93791460bd4591916fae6788dd691570096e47a0e47061cdead407edc2363560/inject.js?id=2f539601-fbea-4ac9-af69-37407fb951b6"></script></body>

  const url = search(address.value, searchEngine.value);
  location.href = __uv$config.prefix + __uv$config.encodeUrl(url);
});
  function cloak() {
    var iframe = document.createElement('iframe');
    iframe.src = window.location.href;
    iframe.style.width = "100%";
    iframe.style.height = "100%";
    iframe.style.border = "none";
    iframe.style.overflow = "hidden";
    
    var newWindow = window.open('about:blank', '_blank');
    newWindow.document.body.appendChild(iframe);
    newWindow.document.body.style.width = "100%";
    newWindow.document.body.style.height = "100%";
    newWindow.document.body.style.margin = "0";
    newWindow.document.body.style.padding = "0";
    
  }

  

body {
  font-family: 'Unbounded', cursive;
  margin: 0;
  background: rgb(0, 0, 25);
  display: flex;
  flex-direction: column;
  min-height: 100vh;
  animation: fadeInAnimation ease-in-out 0.3s;
  animation-iteration-count: 1;
  animation-fill-mode: forwards;
}

.fa-magnifying-glass {
  color: white;
}

.flex-center {
  display: flex;
  justify-content: center;
}

.header-center {
  align-items: center;
  flex-direction: column;
  margin-top: 10%;
}

.left-margin {
  margin: 0px 16px;
}

#uv-error {
  color: #ff6666 !important;
  white-space: pre-wrap;
}

#uv-error-code {
  font-size: 12px;
  color: #fff;
  font-family: "Courier New", Courier, monospace;
}

#uv-register-sw {
  color: white;
  background: #555555;
  cursor: pointer;
  outline: none;
  border: none;
  border-radius: 6px;
  padding: 16px 20px;
  line-height: 16px;
  display: none;
}

#uv-register-sw:active {
  background: #333333;
}

#uv-register-sw.show {
  display: block;
}

.logo {
  width: 105px;
  height: 105px;
  position: absolute;
  top: 345px;
  left: 707px;
} 

.logo-wrapper .text {
  font-size: 75px;
  color: #fff;
}

.logo-wrapper h1 {
  color: white;
}

footer {
  margin-top: auto;
  width: 93%;
  align-self: center;
  height: 80px;
  display: flex;
  justify-content: left;
  align-items: center;
}

footer a,
footer span {
  margin: 0 15px;
  text-decoration: none;
  color: #fff;
  font-size: 15px;
}

footer a {
  cursor: pointer;
}

footer a:hover {
  text-decoration: underline;
}

.desc p {
  width: 560px;
  color: rgba(253, 253, 253, 0.514);
}

form input {
  background: none;
  font-family: inherit;
  padding: 0px 17px;
  height: 48px;
  border: 1px solid rgb(255, 255, 255, 0.2);
  color: var(--text-color);
  border-radius: 3px;
  outline: none;
  width: 350px;
  margin-top: 5px;
  border-radius: 50px;
  color: #fff;
  text-align: center;
}

form input:focus {
  border: 1px solid rgba(253, 253, 253, 0.514);
  border-radius: 6px;
  animation: fadeInAnimation ease-in-out 0.3s;
  animation-iteration-count: 1;
  animation-fill-mode: forwards;
  text-align: center;
}
  // This file overwrites the stock UV config.js

self.__uv$config = {
  prefix: "/uv/service/",
  bare: "/bare/",
  encodeUrl: Ultraviolet.codec.xor.encode,
  decodeUrl: Ultraviolet.codec.xor.decode,
  handler: "/uv/uv.handler.js",
  bundle: "/uv/uv.bundle.js",
  config: "/uv/uv.config.js",
  sw: "/uv/uv.sw.js",
};
  // This file overwrites the stock UV config.js

self.__uv$config = {
  prefix: "/uv/service/",
  bare: "/bare/",
  encodeUrl: Ultraviolet.codec.xor.encode,
  decodeUrl: Ultraviolet.codec.xor.decode,
  handler: "/uv/uv.handler.js",
  bundle: "/uv/uv.bundle.js",
  config: "/uv/uv.config.js",
  sw: "/uv/uv.sw.js",
};
    </html>
