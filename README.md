# ASX
Trading
Skip to content
Navigation Menu
usmanrambo420
/
ASX

Code
Issues
Pull requests
Actions
Projects
Security
Insights
Creating a new file in ASX
BreadcrumbsASX
/
Name your file...
in
main

Edit

Preview
1
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
17
18
19
20
21
22
23
24
25
26
27
28
29
30
31
32
33
34
35
36
37
38
39
40
41
42
43
44
45
46
/ASX-AppBar
    index.html
    styles.css
    script.js
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ASX Application Bar</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="app-bar">
        <div class="app-name">ASX</div>
    </div>

    <script src="script.js"></script>
</body>
</html>
body {
    margin: 0;
    font-family: Arial, sans-serif;
}

.app-bar {
    position: fixed;
    top: 0;
    right: 0;
    background-color: #222;
    color: white;
    padding: 10px 20px;
    z-index: 1000;
    border-bottom-left-radius: 10px;
}

.app-name {
    font-size: 1.2em;
    font-weight: bold;
}
// Add JavaScript functionality here if needed
git init
git add .
git commit -m "Initial commit"
git remote add origin <your-repository-url>
git push -u origin main
New File at / · usmanrambo420/ASX
