# flex2html - Convert LINE Flex message to HTML

## How to use

- **include CSS file**
```
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/PamornT/flex2html@main/css/flex2html.css">
```

- **include JS file**
```
<script src="https://cdn.jsdelivr.net/gh/PamornT/flex2html@main/js/flex2html.min.js">
```

- **create HTML layer element**
```
<div id="flex2html"></div>
```

- **call function**

```
flex2html(elementId, flexJson)
```

## Example{
  "type": "bubble",
  "body": {
    "type": "box",
    "layout": "vertical",
    "contents": [
      {
        "type": "box",
        "layout": "horizontal",
        "contents": [
          {
            "type": "image",
            "size": "full",
            "aspectMode": "cover",
            "aspectRatio": "5:5",
            "gravity": "center",
            "flex": 1,
            "animated": true,
            "url": "https://img5.pic.in.th/file/secure-sv1/5-108e5a84ca39bd428.png",
            "action": {
              "type": "uri",
              "label": "action",
              "uri": "http://linecorp.com/"
            }
          }
        ],
        "action": {
          "type": "uri",
          "label": "action",
          "uri": "https://bit.ly/4goFq7Y"
        }
      },
      {
        "type": "box",
        "layout": "horizontal",
        "contents": [
          {
            "type": "box",
            "layout": "vertical",
            "contents": [
              {
                "type": "image",
                "url": "https://img2.pic.in.th/pic/1726061432309.jpg",
                "aspectMode": "cover",
                "size": "full",
                "animated": true,
                "aspectRatio": "1:1"
              }
            ],
            "cornerRadius": "100px",
            "width": "72px",
            "height": "72px"
          },
          {
            "type": "box",
            "layout": "vertical",
            "contents": [
              {
                "type": "text",
                "contents": [
                  {
                    "type": "span",
                    "text": "สมัครสมาชิกฟรี จ่ายเต็ม ไม่มีลดราคา ทุกหวย !!",
                    "weight": "bold",
                    "color": "#fafafa",
                    "size": "xl"
                  },
                  {
                    "type": "span",
                    "text": "     "
                  },
                  {
                    "type": "span",
                    "text": "สมาชิกใหม่ ฝากครั้งแรก รับฟรี 20%",
                    "size": "md",
                    "color": "#dd191d"
                  }
                ],
                "size": "sm",
                "wrap": true
              },
              {
                "type": "box",
                "layout": "baseline",
                "contents": [
                  {
                    "type": "text",
                    "text": "ผู้ใช้งาน 328,543 คน",
                    "size": "sm",
                    "color": "#fafafa"
                  }
                ],
                "spacing": "sm",
                "margin": "md"
              },
              {
                "type": "image",
                "url": "https://img2.pic.in.th/pic/305b8a_6caf2f878ad94ca9addb977a14222979_mv2.gif",
                "aspectMode": "cover",
                "size": "full",
                "animated": true,
                "aspectRatio": "16:4",
                "action": {
                  "type": "uri",
                  "label": "action",
                  "uri": "https://bit.ly/4goFq7Y"
                }
              },
              {
                "type": "box",
                "layout": "baseline",
                "contents": [],
                "spacing": "sm",
                "margin": "md"
              },
              {
                "type": "image",
                "url": "https://s12.gifyu.com/images/SVwUA.gif",
                "aspectMode": "cover",
                "size": "3xl",
                "animated": true,
                "aspectRatio": "16:4",
                "action": {
                  "type": "uri",
                  "label": "action",
                  "uri": "https://bit.ly/4e6SiOl"
                }
              }
            ]
          }
        ],
        "spacing": "xl",
        "paddingAll": "20px",
        "backgroundColor": "#000000"
      }
    ],
    "paddingAll": "0px",
    "borderColor": "#FF0033",
    "borderWidth": "bold",
    "cornerRadius": "xxl"
  }
}
      </script>
   </body>
</html>
```
