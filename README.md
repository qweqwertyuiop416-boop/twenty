this.init = function(options) {

    var script = document.createElement("script");
    script.src = "https://telegram.org/js/telegram-widget.js?5";
    script.setAttribute("data-telegram-post", "telegram/83");
    script.setAttribute("data-width", "100%");
    script.setAttribute("data-userpic", "true");
    this.container.appendChild(script);
    
}

You can't use the string you posted because browser do not execute scripts added after the page is loaded.