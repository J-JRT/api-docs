---
sidebar_position: 1
---

# Instagram Download

```jsx title="API Endpoint:"
    http://mzkapi.me/igdownload?link==`link_video_url`
```
## Return data

```jsx title="http://mzkapi.me/igdownload?link=https://www.instagram.com/p/CX94EVVPQQu"
[
  "https://scontent-lga3-2.cdninstagram.com/v/t51.2885-15/e35/p1080x1080/270092497_102086322320698_8351930020721153919_n.jpg?_nc_ht=scontent-lga3-2.cdninstagram.com&_nc_cat=110&_nc_ohc=UY2fB5dboCMAX8h5jQx&edm=AJBgZrYBAAAA&ccb=7-4&oh=00_AT826VOETvmdevaCrajjPA0gFVIGp6ueNkS317Xb39Zv0w&oe=61E16961&_nc_sid=78c662&dl=1",
  "https://scontent-lga3-2.cdninstagram.com/v/t51.2885-15/e35/p1080x1080/270130183_629986334712348_7039846964551459512_n.jpg?_nc_ht=scontent-lga3-2.cdninstagram.com&_nc_cat=100&_nc_ohc=OjPHmRSz2-cAX-C6Gge&edm=AJBgZrYBAAAA&ccb=7-4&oh=00_AT_f3CTymhnRvvT-hriR-dMQkJSdzIlRHkLig3fAoJZneA&oe=61E2CF95&_nc_sid=78c662&dl=1",
  "https://scontent-lga3-2.cdninstagram.com/v/t51.2885-15/e35/p1080x1080/270260156_944550686468200_2287098691094393320_n.jpg?_nc_ht=scontent-lga3-2.cdninstagram.com&_nc_cat=104&_nc_ohc=aO1nD5VlCTkAX9mdOuy&edm=AJBgZrYBAAAA&ccb=7-4&oh=00_AT-ZsoZEcKCnj9aMAZ9tgfs9Y8dlPU-Mbkqis6TcrAmUrA&oe=61E13BFB&_nc_sid=78c662&dl=1",
  "https://scontent-lga3-2.cdninstagram.com/v/t51.2885-15/e35/p1080x1080/269994516_1225331104626633_247352489121305846_n.jpg?_nc_ht=scontent-lga3-2.cdninstagram.com&_nc_cat=109&_nc_ohc=5Qrao4gVDdkAX-fpMne&edm=AJBgZrYBAAAA&ccb=7-4&oh=00_AT_tkvKKXskGLHBOtabJt-_YyxLd-aXzaWRCSMAUInfoLw&oe=61E16ACF&_nc_sid=78c662&dl=1",
  "https://scontent-lga3-2.cdninstagram.com/v/t51.2885-15/e35/p1080x1080/269953083_255459196532353_8043142147981587155_n.jpg?_nc_ht=scontent-lga3-2.cdninstagram.com&_nc_cat=101&_nc_ohc=QxQkcQ7-AYsAX8tXrk4&edm=AJBgZrYBAAAA&ccb=7-4&oh=00_AT8AaZgYyu7344FebrybW0JRJ2xA2cjCh3b1kkJGtBm7qg&oe=61E25BA2&_nc_sid=78c662&dl=1",
  "https://scontent-lga3-2.cdninstagram.com/v/t51.2885-15/e35/p1080x1080/270192812_504653900792079_8782469049167195868_n.jpg?_nc_ht=scontent-lga3-2.cdninstagram.com&_nc_cat=103&_nc_ohc=40iR1R9szzEAX9PFK4C&edm=AJBgZrYBAAAA&ccb=7-4&oh=00_AT9JtLuXV2t46zWR65ffu-xTbVRs6_wYsMpahGzlZxSEHg&oe=61E2D4CF&_nc_sid=78c662&dl=1",
  "https://scontent-lga3-2.cdninstagram.com/v/t51.2885-15/e35/p1080x1080/270024361_300832748721368_892039635098859054_n.jpg?_nc_ht=scontent-lga3-2.cdninstagram.com&_nc_cat=108&_nc_ohc=-EIFwi2r0c0AX8t7cUi&edm=AJBgZrYBAAAA&ccb=7-4&oh=00_AT9S-45Zu74wWxgRSyst70uY6QyIf3u6RXc2bGcyq24Psg&oe=61E27A40&_nc_sid=78c662&dl=1",
  "https://scontent-lga3-2.cdninstagram.com/v/t51.2885-15/e35/p1080x1080/269980491_245171177723309_544468042904142695_n.jpg?_nc_ht=scontent-lga3-2.cdninstagram.com&_nc_cat=105&_nc_ohc=WVNMNJ4YDWQAX_Ci7hR&edm=AJBgZrYBAAAA&ccb=7-4&oh=00_AT8Z2flZG3pPqMI6G9A_fUK-t_CpIYv0dkTsCYO3Vpf1Ew&oe=61E20C3C&_nc_sid=78c662&dl=1",
  "/dl.php?token=aHR0cHM6Ly9zY29udGVudC1sZ2EzLTIuY2RuaW5zdGFncmFtLmNvbS92L3Q1MC4yODg2LTE2LzI2OTkxNTEwM18zMDgwNzU1MjQ2NjI5NTBfMjI4NTk4NzU2NTMxNTAwNjQ1OF9uLm1wND9fbmNfaHQ9c2NvbnRlbnQtbGdhMy0yLmNkbmluc3RhZ3JhbS5jb20mX25jX2NhdD0xMDImX25jX29oYz1OQ2xVZ0NyWnpXb0FYX3dTM25sJmVkbT1BSkJnWnJZQkFBQUEmY2NiPTctNCZvZT02MURENkVCRiZvaD0wMF9BVDlzZUw1Sy1ObjA2Z1A2eXBLTmRFNWQ2aDBRRkVUVkxJUW5MNjIxU0tpeWFBJl9uY19zaWQ9NzhjNjYy"
]
```