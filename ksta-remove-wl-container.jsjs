// ==UserScript==
// @name        Ksta.de wl-container entfernen
// @namespace   https://github.com/twelve-cgn/UserScripts
// @match       https://www.ksta.de
// @grant       none
// @version     1.0
// @author      twelve-cgn
// @description Entfernt den Werbe-Container nach dem Laden der Seite.
// ==/UserScript==

(function () {
    window.addEventListener('load', () => {
      [].forEach.call(
        document.querySelectorAll('div.wl-container'),
        el => {
          el.remove;
        }
      );
    }, false);
})()
