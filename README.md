<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Расчёт ипотеки</title>
</head>
<body>
    <iframe id="calcus-iframe" width="100%" height="300" frameborder="0" style="width:1px; min-width: 100%;" scrolling="no" src="https://calcus.ru/kalkulyator-ipoteki?embed=1" referrerpolicy="no-referrer-when-downgrade"></iframe>
<script>
    window.addEventListener('message', function(event) {
        if (event.data['height']) {
            document.getElementById('calcus-iframe').style.height = event.data['height'] + 'px'
        }
    })
</script>
</body>
</html>
