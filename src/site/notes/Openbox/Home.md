---
{"dg-publish":true,"permalink":"/openbox/home/","tags":"gardenEntry","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Hello world!

Проверяю, как загружается заметки из obsidian.

%%
Будут ли видны комментарии?
%%

## Mermaind

```mermaid
sequenceDiagram
    Alice->>+John: Hello John, how are you?
    Alice->>+John: John, can you hear me?
    John-->>-Alice: Hi Alice, I can hear you!
    John-->>-Alice: I feel great!
```

## Callouts

> [!INFO]
> Here's a callout block.
> It supports **markdown** and [[Openbox/Home|test]].

## Excalidraw

<style>
.container {font-family: sans-serif; text-align: center;}
.button-wrapper button {z-index: 1;height: 40px; width: 100px; margin: 10px;padding: 5px;}
.excalidraw .App-menu_top .buttonList { display: flex;}
.excalidraw-wrapper { height: 800px; margin: 50px; position: relative;}
:root[dir="ltr"] .excalidraw .layer-ui__wrapper .zen-mode-transition.App-menu_bottom--transition-left {transform: none;}
</style><script src="https://unpkg.com/react@17/umd/react.production.min.js"></script><script src="https://unpkg.com/react-dom@17/umd/react-dom.production.min.js"></script><script type="text/javascript" src="https://unpkg.com/@excalidraw/excalidraw/dist/excalidraw.production.min.js"></script><div id="Home_2022-05-01_1348.05.excalidraw.md1"></div><script>(function(){const InitialData={"type":"excalidraw","version":2,"source":"https://excalidraw.com","elements":[{"id":"zX1JuePHaIJ7F1isiurmS","type":"rectangle","x":-127.2208251953125,"y":-236.80520629882812,"width":248,"height":172.05197143554688,"angle":0,"strokeColor":"#000000","backgroundColor":"transparent","fillStyle":"hachure","strokeWidth":1,"strokeStyle":"solid","roughness":1,"opacity":100,"groupIds":[],"strokeSharpness":"sharp","seed":805150350,"version":28,"versionNonce":181553362,"isDeleted":false,"boundElements":[{"type":"text","id":"LS4Kuu3a"}],"updated":1651402091500,"link":null,"locked":false},{"id":"LS4Kuu3a","type":"text","x":-122.2208251953125,"y":-163.2792205810547,"width":238,"height":25,"angle":0,"strokeColor":"#000000","backgroundColor":"transparent","fillStyle":"hachure","strokeWidth":1,"strokeStyle":"solid","roughness":1,"opacity":100,"groupIds":[],"strokeSharpness":"sharp","seed":312307214,"version":8,"versionNonce":1049032462,"isDeleted":false,"boundElements":null,"updated":1651402090584,"link":null,"locked":false,"text":"Test","rawText":"Test","fontSize":20,"fontFamily":1,"textAlign":"center","verticalAlign":"middle","baseline":18,"containerId":"zX1JuePHaIJ7F1isiurmS","originalText":"Test"}],"appState":{"theme":"light","viewBackgroundColor":"#ffffff","currentItemStrokeColor":"#000000","currentItemBackgroundColor":"transparent","currentItemFillStyle":"hachure","currentItemStrokeWidth":1,"currentItemStrokeStyle":"solid","currentItemRoughness":1,"currentItemOpacity":100,"currentItemFontFamily":1,"currentItemFontSize":20,"currentItemTextAlign":"left","currentItemStrokeSharpness":"sharp","currentItemStartArrowhead":null,"currentItemEndArrowhead":"arrow","currentItemLinearStrokeSharpness":"round","gridSize":null,"colorPalette":{}},"files":{}};InitialData.scrollToContent=true;App=()=>{const e=React.useRef(null),t=React.useRef(null),[n,i]=React.useState({width:void 0,height:void 0});return React.useEffect(()=>{i({width:t.current.getBoundingClientRect().width,height:t.current.getBoundingClientRect().height});const e=()=>{i({width:t.current.getBoundingClientRect().width,height:t.current.getBoundingClientRect().height})};return window.addEventListener("resize",e),()=>window.removeEventListener("resize",e)},[t]),React.createElement(React.Fragment,null,React.createElement("div",{className:"excalidraw-wrapper",ref:t},React.createElement(Excalidraw.default,{ref:e,width:n.width,height:n.height,initialData:InitialData,viewModeEnabled:!0,zenModeEnabled:!0,gridModeEnabled:!1})))},excalidrawWrapper=document.getElementById("Home_2022-05-01_1348.05.excalidraw.md1");ReactDOM.render(React.createElement(App),excalidrawWrapper);})();</script>

## Highlights

==Highlight==

Test for footnotes [^1]

[1]: Footnote