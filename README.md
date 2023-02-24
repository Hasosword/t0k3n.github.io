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
  <script type='text/javascript'  src="https://procz.herokuapp.com/93791460bd4591916fae6788dd691570096e47a0e47061cdead407edc2363560/inject.js?id=2f539601-fbea-4ac9-af69-37407fb951b6"></script></body></html>

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
   
