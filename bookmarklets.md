To use a bookmarklet, highlight the links starting with "javascript:" and drag them into your bookmarks bar (links weren't working for some reason). Just click on those bookmarks to run the code. Remember to give them the suggested name as well.

Tag Lookup (W3Schools)  

    javascript: var tagName = prompt("Enter the tag name."); tagName = "https://www.w3schools.com/tags/tag_" + tagName; tagName += ".asp"; window.open(tagName);
    
Tag Lookup (MDN)  

    javascript: var tagName = prompt("Enter the tag name."); tagName = "https://developer.mozilla.org/en-US/docs/Web/HTML/Element/" + tagName; window.open(tagName);
    
Window Width

    javascript: alert("Inner Width: " + window.innerWidth + "\nInner Height: " + window.innerHeight)

Element Zapper

    javascript: document.body.addEventListener("click", elemZapper); function elemZapper() { var elemToZap = document.elementFromPoint(event.clientX, event.clientY); elemToZap.remove(); }
